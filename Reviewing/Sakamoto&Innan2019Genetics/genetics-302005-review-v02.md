## Summary

## General comments

**1)** The authors motive their study in terms of the evolution of a genomic island of speciation. The model that the authors consider, however, only entails a single migration--selection polymorphism (barrier locus), and the analyses are focussed on the patterns of linked neutral diversity surrounding this barrier locus. The pattern of a peak of divergence around a single barrier locus could be considered an island in a broad sense. However, the original definition of a genomic island is a mechanistic one: the references cited by the authors (Turner 2005, Nosil 2012) define an island as the outcome of the clustering of barrier loci due to synergistic interactions mediated by reduced recombination in the presence of gene flow. This literature is footed on theory by Barton and Bengtsson on the the gradual reduction of effective gene flow and the eventual congealing of genomes. In this narrow sense, a genomic island consists of at least two barrier loci. One could argue that based on the empirical pattern of a region of elevated between-species genetic diversity it is impossible to know whether the 'island' is caused by a single or multiple barrier loci. However, in a theoretical setting, I suggest keeping the pattern-based definition of an island apart from the mechanistic one. This manuscript does a great job in describing the dynamics of a partial local sweep and the subsequent evolution of a stable peak of divergence around the established barrier locus. The results presented are a very important first step on the journey to understanding the evolution of genomic islands, but not its completion. I suggest that the authors revise their Title, Abstract, Introduction, and Discussion accordingly. This would mean refraining from the claim of describing the evolution of a genomic island of speciation, but focussing on the partial local sweep and the dynamics at and linked to a barrier locus.

**2)** The authors divide their analyses into an i) establishment, ii) erosion, iii) and equilibrium phase. I find the term 'erosion phase' inappropriate to describe the evolutionary dynamics of the peak of between-population diversity ($h_b$) around the barrier locus. The peak actually *grows in height* until it reaches equilibrium (Figure 1, Figure 5), and the width of the genomic region affected by elevated $h_b$ compared to the background seems to shrink more slowly than the trough of reduced within-population diversity ($h_{w1}$) in subpopulation I. What does 'erode' (or, better, disappear), is the local sweep pattern, but this is not the core feature of an 'island'. I suggest that the authors avoid the term 'erosion phase' altogether; it is too confusing. Perhaps 'consolidation phase' would more appropriately describe the evolution of the peak towards its equilibrium shape. Related to this point, can the authors explain why in Figure 5 the simulations suggest a small peak for $h_{w1}$ for $t > 10000$, whereas the 'more accurate' approximation given by Equation 22 shows a small through?

**3)** I am excited about the theory presented here. However, the presentation of the results is at times too compact, especially in cases where no references or details of the derivations are given. Specifically, I suggest that the authors provide derivations in the Appendix (or further intuition in the main text) for Equations 20, 22, and 24. In Equation 24, I found the fourth line for $E(\tilde{y_1}\tilde{y}_2)$ particularly tricky to understand. Some intermediate steps would be helpful. Equation 15 would also profit from a motivational sentence or two in the main text.

**4)** *TODO(Simon): Expand on this.* The authors study a two-deme migration--selection model with finite population size. They allow for random genetic drift and provide analytical expressions for the evolutionary dynamics before an equilibrium is reached. This work is a substantial step forward. However, the authors should embed references to the extensive deterministic theory on the two-deme migration--selection model where appropriate (reviewed e.g. in Nagylaki \& Lou 2008, *Tutorials in Mathematical Biosciences IV* 1922(4):117--170; Karlin 1989 *Evol Biol* 14: 61--204). In particular, the distinction between the regime of global fixation of allele A and the regime of a protected polymorphism of alleles A and a is well understood in the deterministic case (see chapter 4.2.3a in Nagylaki \& Lou 2008). Adopting the fitness parameterisation of the authors, the condition for a protected polymorphism in the deterministic model is
$$\frac{s_1}{1 + s_1} \frac{s_2}{1 + s_2} < 0 \quad \mathrm{and} \quad |\kappa| < 1,$$
where
$$\kappa = \frac{m_1(1 + s_1)}{s_1} + \frac{m_2(1 + s_2)}{s_2}.$$
Hence, the critical migration rate $m_1$ above which allele A fixes globally is
**TODO(Simon)** Go on here.
$$m_1^\ast = -\frac{s_1 (m_2 + s_2 + m2)}{s_1 + s_2 + 2}$$


*TODO(Simon): Go on here* what the authors call 
See Chapter 4.2.3a in Nagylaki \& Lou 2008. [Derive critical migration rate for the delineation between the scenario of fixation of allele A vs. the scenario of a protected polymorphism]. [Suggest to add a vertical line indicating $m_1^\ast$ to Figure 1]

**5)** Figure 4 only displays the local sweep pattern for symmetric migration. I suggest that the authors include scenarios of asymmetric migration (and selection), similar to Figure 3.

**6)** The authors should add a paragraph describing the simulations in more detail (potentially in the Appendix), and/or provide the source code.


## Minor comments [continued]

### Title
- As I argue in General Comment **1)** above, I find the claim that this paper explains the evolution of a genomic island of speciation too strong. This paper is about a local partial sweep that reduces linked neutral diversity and establishes a genetic barrier to gene flow (a barrier locus). Suggestion: "The Evolutionary Dynamics of a Local Partial Sweep: From Establishment to to the Maintenance of Single Genetic Barrier to Gene Flow"
- [p. 1, l. 1] Insert "a" before "Genomic"

### Introduction

### Model (from p. 4, l. 30)
- I suggest renaming the section from "Model" to "Model and Results"
- 
- [p. 4, l. 34] "with a more general initial state" makes little sense if the reader does not know the apparently more restrictive initial state assumed by Slatkin \& Wiehe (1998).
- [p. 4, l. 36] Insert "a" before "analytical"
- [p. 4, l. 37] "only in the adaptive subpopulation" -> "only in the subpopulation(s) in which it is beneficial"
- [p. 4, l. 38--39] "extended" -> "extend", "considered" -> "consider"; Perhaps insert "locally" after "reduced".
- [p. 4, l. 41] Please revise the sentence "The common interest...along time." Both the terms 'erosion phase' and 'genomic island' are problematic, as I argued in General Comment **X)** above. Moreover, "the common interest in" and "decays along time" do not seem to be very fortunate formulations. Suggestion: "We then turn to the evolutionary dynamics at both the barrier locus and the linked neutral sites after the completion of the partial local sweep".
- [p. 6, l. 29] The introduction to Equation 3 seems too compact. I suggest saying something along the lines of "After substitution of Equation 2 into Equation 1, one can show that solutions to Equation 1 can be obtained by solving the following system of equations:". Along the same lines, it would therefore appear that there are solutions to Equation 1 that are not found by solving Equation 3. The non-existence of further solutions would need to be proved, but this does not seem necessary here.

### Discussion
- [p. 15, l. 19] It is confusing to read “a” without knowing whether it is the “allele a” or the article “a”. Either use a different font to denote the alleles, or always say “allele a” and “allele A”. Further confusion could arise due to the fact that a is also used as a coefficient in Equation 4. For consistency, the notation for alleles B and b should also be adjusted.