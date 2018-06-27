# Review of MEC-18-0562 Remi & Whitlock


## Summary
In their manuscript "Background selection and the statistics of population differentiation: consequences for detecting local adaptation", Remi & Whitlock study the effect of variation in the intensity of background selection (BGS) along the genome, and address whether this variation affects the detectability of local adaptation. Accepting that BGS can affect genome-wide average patterns of genetic diversity, the authors focus on locus-to-locus variation in the intensity of BGS as it supposedly arises in real genomes of natural populations. This question is of great interest to the field, as sensible interpretation of patterns of genomic variation requires a detailed understanding of the joint signals of various evolutionary forces, and of the confounding effects individual forces have on the genomic signature of other forces. Remi & Whitlock use their own software to perform forward simulations of an ancestral population that splits into two populations $t$ generations ago. These two daughter populations then may or may not exchange gene flow at a rate $m$. As such, this is the classic and well-studied isolation-with-migration (IM) model. To make these simulations 'realistic', the authors simulate subsamples of the human and stickleback genome. Remi & Whitlock track commonly used summary statistics of genetic diversity within and between populations, including the pairwise nucleotide difference $d_xy$ and the relative population differentiation $F_{\mathrm{ST}}$. The authors compare two estimators of $F_{\mathrm{ST}}$ with different statistical properties, and find that the one introduced by Weir & Cockerham (1984) is largely insensitive to variation in BGS intensity if populations are connected by gene flow. Using their simulations under BGS and neutrality, Remi & Whitlock also find that the false positive rate of an $F_{\mathrm{ST}}$ outlier test aimed at detecting loci under divergent positive selection is not much affected by BGS.  

While Remi & Whitlock address a very important issue in population genomics, the manuscript in its current stage falls short of  providing the necessary evidence to justify some of the stronger claims made by the authors. I feel that more justification is required, as otherwise the work presented here is at risk of being misinterpreted. Along these lines, I would request that the authors embed their hypotheses, findings, and interpretations more carefully in the recent literature about the effects of various forms of selection at linked sites, and use analytical results for simple marginal cases of their scenario to support their simulation results. Unfortunately, the lack of evidence is paired with a number of potential technical flaws (at least, I found it hard to convince myself of the contrary based on the material presented) and some apparent misinterpretations of previous work. Overall, I feel that this amounts to a major revision at least, and requires substantial efforts in any case.



## Major issues

**1.** Test simulations against analytical predictions for marginal conditions, e.g. for a genetic architecture for which an existing BGS model predicts a uniform reduction of effective population size.

**2.** I was dissatisfied by the fact that this study solely uses simulations, while substantial existing theory on BGS could be paired with the structured coalescent under the IM model to explore a much wider parameter space. I am not against simulations, as these are necessary to model complex genomic architectures and demographies. However, without a connection to well-understood marginal cases, I find it difficult to assess the simulated outcomes. The motivation behind the fairly complex simulations done here is to simulate 'realistic' scenarios. However, I am afraid that this 'realism' is compromised by crucial assumptions that should be better supported before they can be used to justify the complexity of the simulations.

**3.** *Choice of parameter values for $m$ and the split time $t$ realistic*? To what extent can the findings obtained here for humans and stickleback be extrapolated to other species? How generally do the findings apply to sticklebacks, even? I presume that e.g. marine vs freshwater ecotypes, and to some extent lake vs stream populations, have quite different demographic histories. Since demographic history may effect the efficacy of selection (including BGS, see e.g. Torres et al. 2017), I am concerned about the generality of the conclusions. As these conclusions are currently stated quite generally, I suggest the authors make it more clear that they are based on two exemplary genomes and a single simple demographic scenario.

**4.** The authors have written an apparently new software (SimBit) for their simulations. While they state that results were double-checked against SFS_code (Hernandez 2008), they do not show these checks (l. 152–155). I suggest the authors show these comparisons, as it would make the verification of their results more transparent.

**5.** Sampling of genomic architectures results in a uniform representation of the genome, but it may also be interesting to compare high- and low-recombination regions in particular. Even if BGS were to create a false signal of local adaptation only in low-recombination regions, this might be enough to produce false positives. *Todo: Complete*.


## Minor comments

C: Comment
Q: Question
S: Suggested change
R: Requested change


### Introduction

- [l. 42–43] R: '...reduce the effective population size of linked loci.' -> '...reduce the effective population size and distort the site frequency spectrum (SFS) of linked lodi.'
- [l. 51–53] S: '..., increasing $F_{\mathrm{ST}}$,...' -> '..., which increases $F_{\mathrm{ST}}$,...'; S: '..., keeping $F_{\mathrm{ST}}$,...' -> '..., which keeps $F_{\mathrm{ST}}$,...'
- [l. 55] C: The mutation ($\mu$) and migration ($m$) rates are not defined at this stage.
- [l. 83–89] C: The first question would seem equally important in tne context of identifying loci under positive selection, as an increased background level of $F_{\mathrm{ST}}$ also alters the power to detect outliers. S: 'Locus-to-locus variation in $F_{\mathrm{ST}$ potentially could...' -> 'Locus-to-locus variation in $F_{\mathrm{ST}$ due to BGS potentially could...'
- [l. 89] S: Perhaps briefly introduce the main reasons for why BGS might vary along the genome already here: i) variation in the intensity of selection (selection coefficient, density of targets of selection and hence mutation rate), ii) variation in recombination rate, iii) effects of other modes of selection at linked sites (e.g. a selective sweep, Hill-Robertson interference).
- [l. 103–105] S: See Aeschbacher et al. (2017) PNAS for a two-step procedure that avoids the confounding effects of BGS on the inference of divergent selection in the face of gene flow.
- [l. 113–117] C: As far as my recollection of the existing literature goes, it is not claimed that $d_{xy}$ should not depend on BGS, but that, as a function of recombination, it should do so in an opposite direction to the effect of divergent selection in the face of gene flow. The argument is then rather that, because BGS reduces the signal of local adaptation on $d_{xy}$ but potentially enhances the signal of local adaptation on $F_{\mathrm{ST}}$, from a conservative point of view, the former ($d_{xy}$) should be preferred over the latter ($F_{\mathrm{ST}}$) as a means of identifying divergent selection. I might be missing specific references supporting the authors' claim, though. In this case, I suggest these references be added.
- [l. 123–125] S: I missed a citation of Elyashiv et al. (2016) here, as they provide a nice example of how a joint model of BGS and positive selection substantially increases the fit to observed, small-scale genomic variation in diversity in *Drosophila* as compared to models with only one mode of selection.


### Methods

- [l. 136–137] C: I missed variation in the strength of selection (i.e. the selection coefficient) as a reason for variation in BGS
- [l. 142] R: If data are not shown, there should be at least a reference.
- [l. 143-145] C: Humans are one of the few mammal species for which a non-LD based recombination map *is* available! See e.g. Kong et al. (2002) Nat. Genet., Kong et al. (2010) Nature, Bhérer et al. (2017) Nat. Commun. I wonder why the authors did not use these resources in order to avoid the bias mentioned on l. 145–148.
- [l. 147–148] S: '..., hence artificially [...] of BGS.' -> '..., which might bias the simulated variance in the intensity of BGS.' 
- [l. 148] S: 'fine scaled' -> 'fine-scaled'
- [l. 168–170] C: I did not see any obvious justification for why mutation rate should vary according to an exponential distribution along the genome. Also, as this part is currently formulated, it is not clear whether the reference to Nachman & Crowell (2000) applies to the mean of 2.5 x 10^–8 only or also to the assumption of the exponential distribution (only the former seems justified). In fact, I think that assuming an exponential distribution of the mutation rate along the genome might be a substantial misspecification, and introduce far too much variation. This assumption might therefore drive much of the observations. To address this concern, I suggest the authors repeat some of their simulations with a constant mutation rate and compare the results to the ones obtained with an exponential distribution.
TODO(Simon): Go on here, commenting on how genomic architecture was sampled (l. 158 ff).


### Results

### Discussion

### Figures and tables

### Supporting material
