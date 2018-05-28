# Review of Am. Nat. manuscript 58395


## Summary

Leimar et al. present a very appealing and neat study on the effect of genetic architecture – in particular, recombination – on the relative contribution of divergently selected among-habitat polymorphisms on the one hand, and modifiers of phenotypic plasticity on the other hand. Using a simple model with one or two among-habitat polymorphisms, as well as two modifiers that code for the relative contributions of these polymorphisms versus an environmental cue, the authors find that if the plasticity genes are tightly linked to the among-habitat polymorphisms, then a steeper reaction norm will evolve as compared to the case where the plasticity genes are unlinked to the among-habitat polymorphisms. The slope of the reaction norm therefore reflects how the trade-off between genetic vs. plastic response to the environment is solved, given the constraints posed by the recombination landscape. The authors then also investigate how recombination rates among and between the ecological polymorphism and the plasticity modifiers evolve in response to this trade-off. This analysis presents another novel contribution, although there seems to be room for a more thorough analysis of the results within the scope of the manuscript. 

The paper is clearly written and there are no major technical flaws. However, I do see a couple of conceptual short-comings that I think would need to be addressed before publication in Am. Nat. can be considered. In particular, there is a fundamental lack of focus on the evolution at the among-habitat polymorphisms, which hampers a complete understanding of the observed results. Moreover, the claim of enhancing our understanding of the evolution of genomic islands of divergence seems overstated, as the analyses of the evolution of genomic islands explicitly ignore the evolution of plasticity.

Another potential issue is the lack of clarity about how terms such as 'evolutionary interest' that seem to be somewhat specific to the inclusive-fitness literature relate to the concepts of fitness and reproductive value, which might me more familiar to a majority of the readers.



## Suggestion

Based on conceptual and technical aspects, reject with minor revisions. Based on scope and innovation, the manuscript may fall short of providing enough novel insight; in particular, the claim of providing novel insight into the evolution of genomic islands of divergence does not seem that sensational given previous work. The major contributions are neat study of the dependence of genetic and plastic determination of phenotypes as a function of genetic architecture, and a simulation experiment showing how recombination is expected to evolve in response to the genes vs. plasticity trade-off.



## Major points

**1.** The motivation of the present study is formulated in terms of the concept of *genetic conflict* between genome elements that differ in *evolutionary interest*. Here, this genetic conflict arises as a consequence of spatially heterogeneous fitness effects of different alleles and genes in two or more populations that inhabit different environments and exchange migrants. While the term *evolutionary interest* of a genomic element is common in the evolutionary-conflict jargon, it is uncommon in the classical population-genetic literature of local adaptation, where individual fitness is the key quantity that is optimised by evolution. It would therefore be useful if the authors could be more explicit about how the evolutionary interest of a genomic element in their sense (*the long-term success of a gene in the sense of representation in future generations*, *reproductive value*) relates to direct individual fitness (the performance of an individual where it *currently* is).

**2.** The population-genetic literature on multilocus models of divergent selection and gene flow has a long tradition and is quite evolved, but it is shallowly represented in the Introduction and Discussion. It would help to be more clear about how the current work connects to previous work, and so be more specific about what is really novel in the former. The importance of recombination (a primary aspect of genetic architecture) for the establishment and maintenance of locally adaptive polymorphisms in the presence of gene flow has been studied exhaustively in previous analytical and simulation studies (for references, see e.g. Bürger & Akerman 2011, Yeaman & Whitlock 2011, Akerman & Bürger 2014, Aeschbacher & Bürger 2014, Yeaman et al. 2016). These studies have identified critical migration and recombination rates below which establishment, maintenance, and clustering of adaptive among-habitat polymorphisms are to be expected. One of the open questions would then be to ask how the presence of generalist plasticity genes (linked or unlinked) affects these properties (establishment, maintenance, clustering) of differentially adapted ecological polymorphisms. But this is exactly what the present study does not do (the evolution of genomic islands is simulated without plasticity genes), and so I think the claim that this study provides novel insight into the evolution of genomic islands is too ambitious.

**3.** Related to the previous point, there is currently a confusion about the primary contribution of the manuscript. The authors seem to be primarily interested in the effect of genetic architecture (essentially recombination rate) on the relative importance of genetics vs. plasticity. My impression is that this is indeed the main point of the paper. The authors also claim to provide novel insight into the evolution of **genomic islands of divergence**. Yet, the simulations investigating the evolution of these islands for a fixed recombination map ignore the effect of plasticity. Indeed, the results of these simulations do not seem to convey any new insight compared to the existing literature (see e.g. the simulation studies by Feder, Nosil, Flaxman and coauthors), and so are more of a confirming than ground-breaking nature.

The authors do, however, go beyond previous work by explicitly simulating the evolution of recombination between ecological polymorphisms, and between the latter and modifiers of the reaction norm. This is indeed novel and of great interest. It would seem appropriate to state that previous theoretical work (which, notably, ignored plasticity) has predicted that the recombination rate among ecological polymorphisms should evolve (e.g. Aeschbacher & Bürger 2014). In principle, the evolution of lower recombination rates between ecological polymorphisms in the presence of gene flow could be classified as a mechanism leading to genomic islands of divergence. The existing literature on the evolution of genomic islands takes the recombination landscape as static (yet not necessarily constant along the genome), and is more concerned with the dynamics of establishment and maintenance of ecological polymorphisms (e.g. Bürger & Akerman 2011, Aeschbacher & Bürger 2014, Ackermann & Bürger 2014) and the evolution of other aspects of the genetic architecture than recombination (e.g. the stacking of small mutations, Yeaman & Whitlock 2011). While there does not seem to be a firm conceptual barrier to breaking with this paradigm, I do think that it matters on what time scales we can expect the recombination rate to evolve, relative to the time scale of mutation and selection on ecological polymorphisms. I feel it would be beyond the scope of the current manuscript to require a thorough investigation of this point. However, I suggest that the authors discuss it to some greater extent.

**4.** I think it is a fundamental shortcoming of the present study that the dynamics at the loci harbouring the divergently selected ecological polymorphisms are not studied. First, I think showing how the allele frequencies change at the $z$ loci would help much to understand the evolution of the reaction norm. Second, I think that the evolution of the reaction norm itself must alter the allele-frequency dynamics at the $z$ loci, at least over a transient period. Specifically, with more plasticity (e.g. a steeper slope), I would expect there to be much less divergence in allele frequencies at the $z$ loci, and ultimately a loss of one of the two alleles by genetic drift. If genes for local adaptation ($z$ genes) are unlinked to the plasticity genes, do you observe weaker or stronger allele-frequency differences in the two habitats at the $z$ loci compared to the case of tightly linkage between local-adaptation and plasticity genes? The remark in l. 204–205 in the description of the simulation model (Methods) points in the direction of a mutual interaction between the $z$ and the $\alpha$ and $\beta$ genes. 

**5.** I was unhappy with the term *statistical information* used to describe what I think is essentially *linkage disequilibrium*. Although *linkage disequilibrium* per se is also an unfortunate term, it is at least historically established in the literature. I acknowledge that sharing of statistical information or similar expressions have been used in the literature, but I would suggest to only use it here if it differs from (gametic) linkage disequilibrium, i.e. from correlations among allele-frequencies arising from gene flow and selection. The current formulation seems unnecessarily fancy, unless I am missing a point here.



## Minor points


I use the following code of abbreviations to classify my points:

Q: question
C: comment
S: suggested change
R: requested change


### Abstract

- C: The first sentence mentions genetic conflict due to transmission patterns as a mechanism. However, it appears to me that the manuscript is not so much concerned about transmission patterns in a narrow sense, but more about a conflict arising from where different genomic elements will be in the future (**destination conflict** *sensu* Gardner & Úbeda 2017).
- C: The claim that the manuscript sheds light on the evolution of genomic islands of divergence seems unjustified (see major points 3 & 4 above).


### Introduction

- [l. 13–15; 18–19] S: Please explain how *pathways of transmission to future generations* and *long-term reproductive success of a gene* relate to fitness. Q: Could the conceptual framework used here also be formulated in terms of fitness, rather than evolutionary interest?
- [l. 34] S: State which sub-category of genetic conflict *ecological genetic conflict* would fall into *sensu* Gardner & Úbeda (2017), i.e. *origin conflict*, *situation conflict*, or *destination conflict*, and say why.
- [l. 47–54] C: I found the use of the term *gene* here somewhat problematic, as you are apparently referring to a *genomic element* *sensu* Gardner & Úbeda (2017). Why not state this definition first?
- [l. 55–57] C: I was struggling with this paragraph, as I would think that genomic islands form among 'genes' with a shared evolutionary interest, and not because of a differences in evolutionary interest.
- [l. 72–74] C: The interaction of genes in an island of divergence and unlinked genes has been studied before. See e.g. Aeschbacher & Bürger (2014) and Yeaman et al. (2016). However, I do think that how reaction norm slopes of plasticity genes evolve under different linkage regimes has not been studied, and here is where I see the scope of this manuscript.
- [l. 112] S: "between habitat genetic polymorphism" -> "between-habitat genetic polymorphism"


### Methods

- [l. 158] C: I found the formulation '...the probability for a dispersing individual to change habitat is $m/2$' unfortunate. Isn't it that, conditional on an individual dispersing, its chance of changing the environment (habitat) is $1/2$, not $m/2$? The *unconditional* probability of changing habitat would seem to be $m/2$.
- [l. 172] S: "...that there are two 'fixed' alleles, $\zeta_1$ and $\zeta_2$,..." -> "...that there are only two alleles with fixed values $\zeta_1$ and $\zeta_2$,..."
- [l. 189] C: It was not entirely clear to me what you mean by 'nearly monomorphic' here.
- [l. 190–200] S: It may be worth stating that the mutational processes at loci $z_1$ and $z_2$ are independent.
- [l. 196] C: The order of the loci will certainly have a quantitative, but perhaps also a qualitative influence. Perhaps say why you consider only this single order.


### Results

- [l. 236–241] R: As stated above (major point 4), I think the allele-frequency dynamics at the $z$ loci are too important for a complete understanding of the model to be ignored.
- [l. 241] R: "...there is single reaction norm..." -> "...there is a single reaction norm..."; "...with steeper slope..." -> "...with a steeper slope..."
- [l. 258–261] C: It would seem that ignoring plasticity here leads to a potentially strong underestimation of the effective migration rate. This seems worth stating more explicitly.
- [l. 270] R: "...of then analysis..." -> "...of the analysis..."
- [l. 276] R: "...for migration rate..." -> "...for a migration rate..."; Q: Have you tried obtaining an analytical approximation to the critical migration rate? It would be interesting to see how your critical value compares to the one derived by Bürger and Akerman (2011).
- [l. 276–282] C: I think this paragraph is a good example of how important it would be to investigate the allele-frequency dynamics at the $z$ loci in order to fully understand the observed patterns.
- [l. 283–290] C: As mentioned above (major point 3), since plasticity is prevented from evolving, I find it hard to see what is novel about these simulations compared to previous work (e.g. by Yeaman & Whitlock 2011).
- [l. 304–308] C/Q: I very much liked the fact that you explore the evolution of recombination rates, as I think this is indeed novel in this specific context. However, have you explored different starting conditions for the $\rho$ parameters? And is there only one or are there several (locally stable) equilibria?
- [l. 309–315] C: I was not entirely convinced by the conclusion that the recombination rates $\rho_{z \alhpa}$ and $\rho_{\alpha \beta}$ did not evolve towards smaller values. The mean $\rho_{z \alpha}$ evolved under an intermediate level of migration ($m = 0.18$) reported in Table 1 differs considerably from the ones evolved under low ($m = 0.12$) and high ($m = 0.24$) migration. The problem seems to be – at least partially – that the simulated distributions of these two evolved recombination rates is bimodal, and so the mean may not be the best summary statistic to report. More fundamentally, however, I was wondering if the bimodality of these two distributions has a biological meaning in terms of reflecting a bistability situation. Moreover, what was the observed correlation between $\rho_{z \alhpa}$ and $\rho_{\alpha \beta}$ over the course of the simulations? Is there any pattern as, for instance, a low $\rho_{z \alhpa}$ whenever $\rho_{\alpha \beta}$ is high and vice versa? Such a dynamics would necessitate a more differentiated interpretation of the results than the one currently given. I am tempted to insist on a more thorough investigation of this point, as from Fig. 5 it appears that the critical migration rate above which no polymorphism is maintained at the two $z$ loci might be between $m = 0.12$ and $m = 0.18$.


### Discussion

- [l. 321–323] C: As mentioned above, the claim that we gain more insight from this study about the evolution of genomic islands in the presence of plasticity seems to be an overstatement, given that in the relevant simulations plasticity does not evolve.
- [l. 340] R: The appropriate reference instead of Aeschbacher et al. (2017) would appear to be Aeschbacher & Bürger (2014). Yeaman & Whitlock (2011) do not seem to derive a new approximation to the effective migration rate.
- [l. 338–346] C: I stumbled over the statement that reproductive values are (perhaps) more informative than effective migration rates. An effective migration rate can be defined in various ways, e.g. as the speed of approach to an internal (polymorphic) allele-frequency equilibrium (e.g. Bürger & Akerman 2011, and adopted e.g. by Yeaman 2015), as the migration rate that would lead to the same stationary allele-frequency distribution under a neutral migration–drift model (Petry 1983), or as the proportion of the future population made up by descendants of immigrants (Charlesworth et al. 1997). All of these derivations converge to the same approximation under the assumption of weak evolutionary forces. Since the quantity derived by Charlesworth et al. (1997) is reminiscent of a reproductive value of immigrant alleles, it may seem worth being more explicit about what exact approximation of the effective migration rate was used here, and how it might be giving different results than the reproductive value.
- [l. 350–351; 362–365] C: As mentioned above (major point 5), the term 'statistical information' sounds a bit magic; I suspect what you refer to is probably simply linkage disequilibrium.
- [l. 362] "...qualitative similar..." -> "...qualitatively similar..."
- [l. 367–371] R: Surely, *recombination* must be added to the mix of driving evolutionary forces here, besides migration and divergent selection.
- [l. 369] S: The correct reference would again seem to be Aeschbacher & Bürger (2014)
- [l. 374–375] S: Some more references to empirical studies would seem appropriate.
- [l. 376–378] R: Delete commas after "main result" in l. 376 and after "(Figs. 2, 3, 5, 6, S1)" in l. 377. Add comma after "is new".
- [l. 402–404] C: As mentioned above, the connection between the main focus of the paper and the evolution of genomic islands of divergence appears to bold here.


### Tables and Figures

- [Table 1] S: In the caption, perhaps use a different notation for the polymorphic complex existing of $z_1$ and $z_2$. The current one ($z_1$ - $z_2$) reads like a subtraction. 
- [Figures 2 and 5] R: I would like to see the equilibrium frequencies of the alleles at the $z$ loci plotted along the results shown. At least, it should be visible at which point the polymorphism at the $z$ loci is lost. Moreover, I was wondering why the intercept ($\alpha$) and slope ($\beta$) continue to evolve at a reduced rate after the kinks in the respective curves, as a function of the migration rate. Please add a short clarification/explanation. In the caption of Fig. 5, line 8: "replicate" -> "replicates". Q: For the scenario of 'full' linkage, the recombination rates were set to 0.001, so strictly speaking this is not full linkage. If you were to set these rates to 0, would the outcome depend on the initial conditions (i.e. the initial haplotypes present)?
- [Figures 3 and 6]: R: Please label the x axis. C: I found the use of *generalist* and *specialist* as done here in these captions somewhat problematic, since a genetic generalist (homozygote for one or the other allele at each of the $z$ loci) can be (or evolve into) a plastic generalist.
- [Figure 7] R: As mentioned earlier, the bimodal distribution of evolved recombination rates requests a more illuminating explanation. Also, given the values in Table 1, it would be interesting to see the distributions of the recombination rates for $m = 0.18$ in Fig. 7 as well. 


### Appendix A

#### Numerical analyses

- [p. 28, Eq. A4] S: I think it would be better to explicitly add both the terms $P_{i12}$ and $P_{i21}$, and multiply these heterozygote genotype frequencies by 1/2, rather than saying that the equivalence has been taken into account.
- [p. 29, last two lines] S: For clarity, I suggest using a different notation for $p_{ik}$ and its equilibrium (e.g. adding a hat to the latter).

#### Mutant invasion

- [p. 30, l. 1–4] R: It was not clear to me what you assume about the recombination rates $\rho_{z \alpha}$ and $\rho_{\alpha \beta}$ in these invasion analyses. Please (re-)state explicitly. Similarly, it is therefore also not entirely clear whether a given modifier only either modifies one of the alleles (the linked one) at the $z$ locus or one of the plasticity genes ($\alpha$, $\beta$). Or whether a given modifier can simultaneously affect one of the alleles at the $z$ locus as well as $\alpha$ and/or $\beta$. Please clarify.
- [p. 30, last four lines] R: The sentence about recombination seems to be broken; at least I did not understand what exactly you wanted to say. Please fix.
- S: It would help to state explicitly that you assume that the resident populations (and hence the mean fitnesses) are assumed not to be affected by the invasion of the modifier.

#### Invasion fitness
- [p. 31, last paragraph] C: Did you artificially retain the polymorphism at the $z$ locus? If so, I wonder how biologically meaningful the results are. If the polymorphism were lost if you did not retain it, surely you would observe different invasion dynamics for the modifier, and potentially also at the plasticity genes.

### Supporting tables and figures

- [Table A1] R: In the second part of the caption, "...with linkage $\rho$ the the..." -> "...with recombination rate $\rho$ to the...".
- [Fig. A1] S: As for Figs. 2 & 5, it would be helpful if the equilibrium allele-frequencies at the $z$ locus were shown, as well. In the caption (second-to-last line): "...$\rho$ between between the genetic..." -> "...$\rho$ between the genetic...".
- [Fig. A2] In the caption: R: "...described main text..." -> "...described in the main text..."; "...we extend to the..." -> "...we extent this to the...". C: In the simulations, a recombination rate of $\rho = 0.002$ seems very low compared to the migration rate $m = 0.06$. Therefore, the evolution of genomic islands is not too surprising. It would be interesting to know at what recombination rate the evolution of genomic islands breaks down, and how this threshold relates to critical recombination rates reported e.g. in Aeschbacher & Bürger (2014).
