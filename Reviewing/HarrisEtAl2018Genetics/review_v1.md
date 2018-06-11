# Summary

In a very well-written manuscript that seems technically flawless, Harris et al. present an approach for detecting and classifying selective sweeps from unphased multilocus genotypes (MLGs). The method extends the haplotype-homozygosity based approach of Garud et al. (2015) multilocus genotype (MLG) identity. Although there are now several methods for detecting selective sweeps based on linkage disequilibrium or extended haplotype homozygosity, all of them except for the one by Garud et al. (2015; NR Garud being a coauthor of the present manuscript, too) lack the ability to distinguish between hard and soft sweeps. Garud et al. (2015) have shown that the ratio of the haplotype homozygosity for all but the most frequent haplotype (H2) to the overall haplotype homozygosity (H1) has power to delineate soft and hard selective sweeps. This discrimination power depends on a statistic H12 (H123) that represents the haplotype homozygosity after the two (three) most frequent haplotypes have been pooled, and which has power to detect but not categorise sweeps.

The significance of the approach by Harris et al. is hat the MLG analoga to the H-statistics, i.e. G1, G2, G12(3), can be computed from non-phased data. This is a major asset given that phased genomic data are still scarcely available beyond a small set of model organisms, and so extends the applicability of the framework substantially. Yet, the conceptual innovation and originality of the manuscript appears to be within narrow bounds given the previous work by Garud et al. (2015). Harris et al. do make an important contribution though by thoroughly testing the robustness of their MLG homozygosity approach to confounding factors including population bottlenecks, population expansions, balancing selection, background selection, and the way missing data are deatl with. The authors perform forward simulations to measure the power to detect sweeps under these various scenarios, and to assess the ability to discriminate between soft and hard sweeps. Harris et al. illustrate their results in a visually very appealing way. The authors also apply their approach to phased haplotype data from four populations of the 1000 Genomes project. They corroborate previously identified sweeps, but also indentify novel ones. A pronounced difference between African (YRI) and non-African (CEU, GIH, CHB) populations in the relative abundance of identified hard vs. soft sweeps calls for an explanation and should be discussed to some larger extent.

Harris et al. find that the MLG identity statistics have generally high power to detect sweeps, and to classify them as soft or hard in substantial parts of the space of the MLG statistics. In particular, the methods is fairly robust against deviations from a constant-size demographic history and to background selection. Generally, detection power is highest for strong and recent sweeps, as expected. However, balancing selection can severely interfere with the detection power and lead to a high false-postitive rate. The authors also study the effect of admixture masking some of the sweep signal, and find that if single-pulse admixture proportions are sufficiently low (< 0.3), then their MLG statistics retain power to detect a hard sweep.

I think that the manuscript is of high interest and very nicely done. I did have a few concerns (see below) related to the robustness and biological scope, as well as to the assumption of Hardy-Weinberg equilibrium. Overall, I am undecided as to whether in its current state the manuscript qualifies for publication in GENETICS, since, from a technical point of view, it is to a large extent of an extending, rather than innovative, nature. I think the latter concern could be removed if some of the major concerns mentioned below (false positives under admixture, robustness to non-random mating, visualisation of simulated likelihood surfaces) were included, as these points would on their own add substantial biological insight and guide future applications of the method. That said, the manuscript is quite long already, and I suggest that the authors make another effort to shorten it. I feel there is quite some scope for condending the main text, especially by removing redundancy in the description of the methods or moving some of it to the supporting information.



# Major concerns

**1.** The principal reasoning underlying the new approach by Harris et al. is that the most frequent haplotypes yield the most frequent (homozygous) MLGs. However, this holds only under the assumption of random mating. In certain organisms, such as plants that (partially) self, or in populations with a cryptic population structure, mating is not random. Natural selection, too, may lead to a distortion of Hardy-Weinberg proportions at least temporarilly. Therefore, it would seem appropriate if the authors tested the robustnes of their method to deviations from the assumption of random mating (e.g. due to partial selfing or cryptic population structure).

**2.** While the authors study the effect of admixture masking an existing hard sweep, they leave unaddressed the question of whether and to what extent admixture alone can create false-positive (soft-)sweep signatures. I think this should be addressed with another set of simulations focussed on establishing the effect on detection and classification power as a function of admixture strength and time. See also major concern **5.** below.

**3.**  The authors do not report how the power of their approach to discriminate between hard and soft sweeps relates to the frequency with which test combinations of G12 (G123) and G2/G1 are encountered in their simulations, given their prior believes in model parameters. In other words, it is unclear how often biological systems occupy the summary-statistics space for which detecion and discrimination power are highest. Figures 5, 6, and S6 are very nice and provide much insight. It would be desirable, though, that the authors also showed the joint distribution of the simulated statistics, e.g. of the (G12, G2/G1) values in the case of Figure 5 A and B, separately for hard and soft sweeps. This would reveal how the ability to distinguish between the two types of sweeps relates to the ferquency at which the test-value combinations are to be expected. If Bayes factors are high or low only in situations that have a very low absolute frequency, then this would somewhat reduce the encouraging results shown in terms of method power and Bayes factors only.

**4.** Related to the previous concern, the reader's intuition of what makes the MLG identity statistics powerful statistics could be increased if the authors visualised the simulated (i.e. empirical) probability mass function of the G statistics as a function of the parameters (as a proxy of the joint likeihood function). This would approximate the marginal distribution of each of the statistics (e.g. G123, or G2/G1) as a joint function of the start time (t) and strength (s) of the sweep, and could be done for a small set of meaningful combinations of f and k.

**5.** The applications to a subset of the 1000 Genomes data reveal the striking pattern that the YRI show a much larger relative proportion of soft vs hard sweeps, as compared to the CEU, GHI, and CHB populations. I was wondering if, besides the out-of-Africa bottneleck(s) and subsequent adaptation explaining a potential excess of recent hard sweeps in non-African populations, underappreciated admixture in YRI (e.g. Busby et al. 2016, eLife, doi: 10.7554/eLife.15266) could have created some apparent soft-seep signals, and so be part of the explanation of this striking difference. A detailed investigation of this question seems beyond the scope of the paper. However, I think that addressing major concern **2.** above will provide some insight, and the issue deserves some more discussion in the main text. 



# Minor comments


Abbreviations used:
- C: comment
- Q: question
- S: suggested change [a -> b means replace a by b]
- R: requested change [a -> b means replace a by b]


## Abstract
- [Second-to-last sentence] S: "...based on human parameters.." -> "...based on parameters compatible with our recent understanding of human demography..."


## Introduction
- [p. 3, l. 3] S: "...signatures, hard sweeps and soft sweeps,..." -> "...signatures, those of hard sweeps and soft sweeps, respectively,..." [I think the formulation depends on whether a sweep is considered a process or a pattern; I favour the former]
- [p. 3, l. 21] S: "selected allele" -> "one of the selected alleles"
- [p. 4, l. 1] R: Fix citation style for Chen et al. (2015)
- [p. 4, l. 7] S: "...computed as expected..." -> "...computed as the expected..."
- [p. 4, l. 17] S: "...is expected haplotype..." -> "...is the expected haplotype..."
- [p. 4, l. 25] S: "...MLGs are a single string representing a..." -> "MLGs are single strings representing a..."


## Results
- [p. 8, l. 31] R: "...produces..." -> "...produce..."
- [p. 11, l. 23] C: Here and throughout the rest of the paper, I found the use of "parameter space" inappropriate, as the G and H statistica are not parameters, but summary statistics. I suggest using a different term.
- [p. 12, l. 31] R: Fix citation style for Huber et al. (2016)


## Discussion
- [p. 14, l. 28] S: "...sweeps, resulting in a..." -> "...sweeps, which results in a..."
- [p. 15, l. 1] S: "...further back in time..." -> "...if they started far enough back in time..."
- [p. 15, l. 4] R: "...allele decreases." -> "...allele decreases due to recombination."
- [p. 15, l. 6–9] C: The flip side perhaps worth mentioning is that it is difficult to detect and classify weak positive selection.
- [p. 16, l. 26–30] S: Remind the reader of how the Bayes factor was designed, i.e. that it is P[soft]/P[hard], not the inverse.
- [p. 19, l. 25–28] C: It seems very plausible that G12 and G123 (or H12 and H123) have weak power to distinguish an almost complete hard sweep from balancing selection if h approaches 1, as the latter is then close to directional selection. However, I was wondering if the authors could add G2/G1 into the mix here, and see if the combination of G12 and G2/G1 has more power to differentiate between a hard sweep and balancing selection than has G12 (G123) alone.
- [p. 19, l. 32] S: "...reduction in nucleotide diversity,..." -> "...reduction in nucleotide diversity and a distortion of the site-frequency spectrum,..."
- [p. 20, l. 12–14] C: Besides obscuring the true signal of a sweep, admixture (from a ghost population) may also create a false signal of a sweep, and so I think the authors should assess the false-positive rate under simulations of a neutral admixture scenario, with varying admixture times and proportions. See major concern **2.** above.
- [p. 21, l. 25] S: Based on the results shown, it seems bold to claim that the method by Harris et al. provides a means of distinguishing sweeps from balancing selection without saying that this distinction is restricted to a set of conditions that is hard to verify in practice. It would seem more conservative to claim that the method can differentiate between selective sweeps and background selection.
- [p. 21, l. 26] S: "...differentiation lends itself well for use as a..." -> "...differentiation motivates the use of MLG identity statistics as a..."


## Materials and Methods
- [p. 22, l. 7] S: Add recombination as a process simulated by SLiM 2
- [p. 23, l. 11] S: "...heterozygote advantage selection..." -> "...heterozygote-advantage selection..."
- [p. 23, l. 16] R: Insert a comma after both occurrences of "G2/G1" in this sentence.
- [p. 23, l. 25–26] R: Please specify the base of the logarithming prior scales.
- [p. 24, l. 3] C: The authors seem to use $N$ to denote both the haploid and diploid population size, depending on the context. As this is confusing, I suggest to change this.
- [p. 24, l. 25–28] S: "Balancing selection simulations..." -> "Simulations of balancing selection...". C: To be more precise, I suggest using "overdominant directional selection" to describe what the authors currently call "balancing selection". At least, this specification should be made once, if the authors want to stick to the term "balancing selection" in the remainder of the paper.
- [p. 25, l. 1] S: "...our single background selection scenario..." -> "...our single background-selection scenario..." 
- [p. 26, l. 10] S: "...spatial signature..." -> "...genomic signature..."
- [p. 26, l. 21–22] S: "...under a constant population size demographic history..." -> "...under the demographic scenario of a constant population size..."
- [p. 28, l. 1–5] R: Please split this sentence, it seems too long. Q: How important is this additional filter for mappability and alignability?

## References
- [p. 35] S: "GENETICS" -> "Genetics" in reference to Loh et al (2013)
- [p. 36] C: Volume (and issue) missing for reference to Muhlfeld et al. (2009)

## Figures
- [Figure 2] S: I suggest the authors add an illustration of the admixture model (this could also be a figure in the supporting information).

## Supporting Material
- [Figure S4] R: Please remind the reader of the selection coefficient used for the results shown.
- [Figures S7 and S8] C: For Chromosome 2, it is not clear if all the gene names refer to the same peak (around 136 Mb) unless one also considers Figure 7. Q: What is the difference between the black and grey lines? C: This is a detail, but it appears as if the visualisation linearly interpolates across gaps due to missing information, which does not seem desirable.
- [Figures S19 and S20]: R: Please make the legend labels more self-explanatory. In the caption, replace "...to detect sweeps." by "...to detect hard sweeps.".
