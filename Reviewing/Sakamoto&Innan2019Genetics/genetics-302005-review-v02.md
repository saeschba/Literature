## Summary

## General comments

**1)** The authors motive their study in terms of the evolution of a genomic island of speciation. The model that the authors consider, however, only entails a single migration--selection polymorphism (barrier locus), and the analyses are focussed on the patterns of linked neutral diversity surrounding this barrier locus. The pattern of a peak of divergence around a single barrier locus could be considered an island in a broad sense. However, the original definition of a genomic island is a mechanistic one: the references cited by the authors (Turner 2005, Nosil 2012) define an island as the outcome of the clustering of barrier loci due to synergistic interactions mediated by reduced recombination in the presence of gene flow. This literature is footed on theory by Barton and Bengtsson on the the gradual reduction of effective gene flow and the eventual congealing of genomes. In this narrow sense, a genomic island consists of at least two barrier loci. One could argue that based on the empirical pattern of a region of elevated between-species genetic diversity it is impossible to know whether the 'island' is caused by a single or multiple barrier loci. However, in a theoretical setting, I suggest keeping the pattern-based definition of an island apart from the mechanistic one. This manuscript does a great job in describing the dynamics of a partial local sweep and the subsequent evolution of a stable peak of divergence around the established barrier locus. The results presented are a very important first step on the journey to understanding the evolution of genomic islands, but not its completion. I suggest that the authors revise their Title, Abstract, Introduction, and Discussion accordingly. This would mean refraining from the claim of describing the evolution of a genomic island of speciation, but focussing on the partial local sweep and the dynamics at and linked to a barrier locus.

**2)** The authors divide their analyses into an i) establishment, ii) erosion, iii) and equilibrium phase. I find the term 'erosion phase' inappropriate to describe the evolutionary dynamics of the peak of between-population diversity ($h_b$) around the barrier locus. The peak actually *grows in height* until it reaches equilibrium (Figure 1, Figure 5), and the width of the genomic region affected by elevated $h_b$ compared to the background seems to shrink more slowly than the trough of reduced within-population diversity ($h_{w1}$) in subpopulation I. What does 'erode' (or, better, disappear), is the local sweep pattern, but this is not the core feature of an 'island'. I suggest that the authors avoid the term 'erosion phase' altogether; it is too confusing. Perhaps 'consolidation phase' would more appropriately describe the evolution of the peak towards its equilibrium shape. Related to this point, can the authors explain why in Figure 5 the simulations suggest a small peak for $h_{w1}$ for $t > 10000$, whereas the 'more accurate' approximation given by Equation 22 shows a small through?

**3)** I am excited about the theory presented here. However, the presentation of the results is at times too compact, especially in cases where no references or details of the derivations are given. Specifically, I suggest that the authors provide derivations in the Appendix (or further intuition in the main text) for Equations 20, 22, and 24. In Equation 24, I found the fourth line for $E(\tilde{y_1}\tilde{y}_2)$ particularly tricky to understand. Some intermediate steps would be helpful. Equation 15 would also profit from a motivational sentence or two in the main text.

**4)** The authors study a two-deme migration--selection model with finite population size. They allow for random genetic drift and provide analytical expressions for the evolutionary dynamics before an equilibrium is reached. This work is a substantial step forward. However, the authors should embed references to the extensive deterministic theory on the two-deme migration--selection model where appropriate (reviewed e.g. in Nagylaki \& Lou 2008, *Tutorials in Mathematical Biosciences IV* 1922(4):117--170; Karlin 1989 *Evol Biol* 14: 61--204). In particular, the distinction between the regime of global fixation of allele A and the regime of a protected polymorphism of alleles A and a is well understood in the deterministic case (see chapter 4.2.3a in Nagylaki \& Lou 2008). Adopting the fitness parameterisation of the authors, the condition for a protected polymorphism in the deterministic model is
$$\frac{s_1}{1 + s_1} \frac{s_2}{1 + s_2} < 0 \quad \mathrm{and} \quad |\kappa| < 1,$$
where
$$\kappa = \frac{m_1(1 + s_1)}{s_1} + \frac{m_2(1 + s_2)}{s_2}.$$
Hence, the critical migration rate $m_1$ above which allele A fixes globally is
$$m_1^\ast = -\frac{s_1 (m_2 + s_2 + m_2 s_2)}{(1 + s_1) s_2}.$$
For instance, for the parameters in Figure 3A, $m_1^\ast \approx 0.021$, which is substantially higher than the left-hand boundary of the grey area that encompasses the range of values of $m_1$ for which $0.1 \le Pc \le 0.9$. Here, $Pc$ is the proportion of simulations in which alleles A and a were found to coexist, as defined by the authors. I suggest the authors add a vertical line indicating $m_1^\ast$ to each panel in Figure 3, and that they explain why $m_1^\ast$ is higher than their (somewhat arbitrary) threshold of $Pc = 0.1$. 

**5)** Figure 4 only displays the local sweep pattern for symmetric migration. I suggest that the authors include scenarios of asymmetric migration (and selection), similar to Figure 3.

**6)** The authors should add a paragraph describing the simulations in more detail (potentially in the Appendix), and/or provide the source code.

**7)** The manuscript seems technically flawless. However, there are quite a few linguistic problems throughout the paper that require thorough revision. See minor comments below.


## Minor comments

### Title
- As I argue in General Comment **1)** above, I find the claim that this paper explains the evolution of a genomic island of speciation too strong. This paper is about a local partial sweep that reduces linked neutral diversity and establishes a genetic barrier to gene flow (a barrier locus). Suggestion: "The Evolutionary Dynamics of a Local Partial Sweep: From Establishment to to the Maintenance of Single Genetic Barrier to Gene Flow"
- [p. 1, l. 1] Insert "a" before "Genomic"

### Introduction
- [p. 1, l. 12--13] "when" -> "if"; "in the adaptive subpopulations...in others" -> "in the subpopulations in which it is adaptive, but not in the ones in which it is deleterious."
- [p. 1, l. 13--16] "regions" -> "region"; "are" -> "is"; insert "the" after "along". As stated in General Comment **1)** above, I find this broad-sense definition of a genomic island of speciation not helpful in this context. "We are interested...to stable preservation" -> "We are interested in the evolutionary dynamics of a genetic barrier to gene flow, from its establishment via a partial local sweep to the emergence of a peak of divergence to its stable preservation." (or similar).
- [p. 1, l. 17--18] At present, this sentence is formulated as a possibility. I suggest reformulating it to an affirmative statement, i.e. a description of what you do in the paper, not of what could be done.
- [p. 1, l. 19--21] Please rephrase this sentence to be more clear. Is it necessary to introduce both $\pi$ (here) and $h$ (later)? I suggest arguing in terms of diversities (heterozygosities) throughout, and so only using the symbol $h$ (with subscripts, of course).
- [p. 1, l. 22] "numbers" -> "number"
- [p. 1, l. 30] "selective sweep" -> "partial selective sweep"
- [Figure 1] Please add the times since the start of the simulation to each row of panels. Please indicate the values of $N_i$, $s_i$, and $m_i$ ($i = 1,2$). Panel B: I found it hard to believe that the two figures (left and right) correspond to each other. If the locally adaptive mutation has fixed in subpopulation I, but is absent from subpopulation II, should there not be a peak of $\pi_b$ at position 0? Panels B to E: I suggest making clear that the locally adaptive mutation will not fix in subpopulation I, and that it will be present at low frequency in subpopulation II. Specifically, why not moving one of the yellow asterisks from subpopulation I to subpopulation II? Caption: The sentence "The y-axis is adjusted..." did not make sense to me. Please clarify. "if the population recombination rate = 0.001 per site is assumed" -> "if a population-scaled recombination rate of $N r = 0.001$ (or $4Nr = 0.001$?) per site is assumed"
- [p. 3, l. 1--4] This sentence is confusing. Please rephrase it. Moreover, I looking at Figure 1B, I do not agree that the initial 'island' is as wide as the trough in diversity within subpopulation I. There is essentially no elevation in between-population diversity yet.
- [p. 3, l. 4] As argued above in General Comment **2)**, I would refrain altogether from using the term 'erosion phase'; 'consolidation phase' seems more appropriate.
- [p. 3, l. 39--40] "difficult to handle and have" -> "difficult to handle, and it has"
- [p. 4, l. 1] "quite straightforward because of" -> "facilitated by" / "simplified by"
- [p. 4, l. 21] "very" -> "sufficiently"
- [p. 4, l. 26] "worthy to note" -> "worth noting"
- [p. 4, l. 27] "nice analytical approximate formula" -> "elegant analytical approximation" (?). I wonder if the sentence is needed at all.
- [p. 4, l. 34] "with a more general initial state" makes little sense if the reader does not know the apparently more restrictive initial state assumed by Slatkin \& Wiehe (1998).
- [p. 4, l. 36] Insert "a" before "analytical"
- [p. 4, l. 37] "only in the adaptive subpopulation" -> "only in the subpopulation(s) in which it is beneficial"
- [p. 4, l. 38--39] "extended" -> "extend", "considered" -> "consider"; Perhaps insert "locally" after "reduced".
- [p. 4, l. 41] Please revise the sentence "The common interest...along time." Both the terms 'erosion phase' and 'genomic island' are problematic, as I argued in General Comments **1)** and **2)** above. Moreover, "the common interest in" and "decays along time" do not seem to be very fortunate formulations. Suggestion: "We then turn to the evolutionary dynamics at both the barrier locus and the linked neutral sites after the completion of the partial local sweep".
- [p. 4, l. 43] "in the adaptive population" -> "in the respective population"
- [p. 4, l. 46 to p. 5, l. 7] Yeaman et al. (2015) predominantly focussed on the evolution of an island due to the clustering of two barrier loci in the face of gene flow. The secondary-contact scenario was of minor interest. Here, the authors create the impression that the secondary-contact scenario was the main focus of that earlier study, and they do not mention that Yeaman et al. (2015) studied two barrier loci. Please adjust this. Also, note that one of the points made by Yeaman et al. (2015) was that, at equilibrium and all else being equal, the shape of a two-barrier island is the same under the de novo scenario as under the secondary-contact scenario.
- [Figure 2] Please add $y_{a1}$, $1 - y_{a1}$, $y_{a2}$, and $1 - y_{a2}$ at the appropriate positions. The caption should be extended 

### Model
- I suggest renaming the section from "Model" to "Model and Results".
- [p. 5, l. 16--18] "We consider...reproduction" -> "We consider a two-population model with discrete generations and monoecious diploid individuals that mate at random." The addition "which follows the Wright--Fisher reproduction" does not seem necessary, because it is redundant with the rest of the description.
- [p. 6, l. 3] It is unfortunate that $u$ is used both for the mutation rate at locus B and for the establishment probability of allele A at locus A.
- [p. 6, l. 4] I suggest rephrasing such that the sentence does not start with the symbol "r".
- [p. 6, l. 14--18] "Following previous studies (Haldane 1927)...increases" -> "Following Haldane (1927), we approximate the establishment probability by the probability that the new mutation increases..."; "with the assumption" -> "under the assumption"; "allele" -> "mutation"
- [p. 6, l. 19] The symbol $u$ was already used for the mutation rate at locus B.
- [p. 6, l. 26--27] "Because the extinction probability of each individual mutation is independent to each other" -> "Because the extinction probabilities of individual mutations are independent"
- [p. 6, l. 28] Note that $\psi_i$ has not been explicitly defined.
- [p. 6, l. 29] The introduction to Equation 3 seems too compact. I suggest saying something along the lines of "After substitution of Equation 2 into Equation 1, one can show that solutions to Equation 1 can be obtained by solving the following system of equations:". Along the same lines, it would therefore appear that there are solutions to Equation 1 that are not found by solving Equation 3. The non-existence of further solutions would need to be proved, but this does not seem necessary here.
- [p. 6, l. 30] "Then, the above equations deduce" -> "Equation 3 can be rearranged to"
- [p. 7, l. 2] "cubic equation" -> "cubic equations"
- [p. 7, l. 16] Omit "the" in front of "migration rate"
- [Figure 3] Last sentence of the caption: As the reader likely encounters $Pc$ for the first time here (before coming across the definition in the main text), I suggest spelling out what $Pc$ means here.
- [p. 9, l. 8] Subsection header: Set "et al." to italic bold face.
- [p. 9, l. 10] I find the long subscripts to $D$ unfortunate ("Stephan et al.",  "modified Stephan et al.", "local sweep"; see also Equations 9, 10, and 16). Could you just use $D$, $D^\prime$, and $D_{\mathrm{ls}}$ instead?
- [p. 10, l. 8] Delete "maladaptive".
- [p. 10, l. 10] "could" -> "can"
- [Figure 4] Please indicate the values of $s_1$ and $s_2$.
- [p. 11, l. 11] "As going further" -> "Moving away"
- [p. 11, l. 12] "It is indicated that" -> "This is because" (?)
- *TODO(Simon): Go on here*

### Discussion
- [p. 15, l. 19] It is confusing to read “a” without knowing whether it is the “allele a” or the article “a”. Either use a different font to denote the alleles, or always say “allele a” and “allele A”. Further confusion could arise due to the fact that a is also used as a coefficient in Equation 4. For consistency, the notation for alleles B and b should also be adjusted.