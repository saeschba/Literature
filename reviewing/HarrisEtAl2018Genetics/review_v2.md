# Summary

The authors have carefully addressed all the concerns that I had, and I am very satisfied with the respective revisions. I think the paper will make a substantial contribution to the evolutionary genetics community. I very much appreciate the new simulations under scenarios of a structured population with gene flow and of pulse of admixture with a ghost population. As the authors acknowledge, admixture with a small enough ghost population at the right point in time can mimic the signature of a soft sweep, at least in terms of haplotype homozygosity and multilocus genotype (MLG) statistics. I regret that the authors have entirely excluded their analyses of balancing selection, which had shown that such selection can also limit the power to correctly identify sweeps. I understand that this decision was taken with the aim of shortening the manuscript. The new part on inferring the number of sweeping haplotypes is of high interest, as it avoids the need for a rigorous classification of sweeps in scenarios where MLG statistics provide ambiguous results.

Reading the manuscript and the supporting information carefully again, I found a few minor issues (see minor comments below) that should be straightforward to address. However, I have one remaining major concern related to the use of the terms "expected homozygosity method" and "expected homozygosity statistic":


# Major concern

Since the MLG statistics conceptually are clearly *not* expected homozygosity statistics, and in practice likely quite sensitive to the most frequent heterozygous haplotype combination (e.g. page 5, lines 5-6), I would argue for a more differentiated use of "expected homozygosity method/statistic" throughout the manuscript. It appears to me that the authors have introduced these terms at multiple occasions during their revisions. I plea for maintaining the terms "(expected) homozygosity statistic method/statistics" vs. "multilocus genotype method/statistics" clearly distinct. Good examples of such a distinction are on page 11, lines 7-8 or page 12 throughout.

Examples of where I find the term "(expected) homozygosity method/statistics" problematic are:  Page 9, lines 26-27 and 32; page 10, lines 2-3, 11, 15, 20; page 16, lines 1, 10 and 22; page 17, lines 1 and 22; page 22, lines 6, 7; page 23, lines 6 and 21; captions of Fig 1, . The use of "MLG homozygosity" is also problematic at the following positions, especially in the context of soft sweeps: Page 8, line 16; page 9, line 1; page 16, line 7. In many cases, the problematic terms might be replaced by "MLG genotype statistics/method" or similar.

I must admit that I have overlooked a small number of such occurrences in the first round of review, and my focus on this issue has been motivated by the comments of the other reviewers. Most of the problematic occurrences of "homozygosity statistics/method" are in the revised portion of the text, however. Overall, the strong emphasis on homozygosity seems odd given the new sentence on page 5, lines 5-6, and the mentioning of the XY genotype as contributing to the signal there. The new sentence "...our approach assumes elevated MLG homozygosity derives from elevated haplotype homozygosity" reads strange, because this assumption does not actually seem to be present in Eqs. (2) and (3) and is not beyond the default assumption of Hardy-Weinberg proportions. Accordingly, the empirical data (Fig. 7) seem to show that the most frequent heterozygous MLG contributes substantially to G12, especially in YRI and GIH. The addition of the new figure Fig. S4 is very nice, but it would be even better to indicate for each bar-compartment if it represents a homozygous or a heterozygous MLG genotype.


# Minor comments

Article summary: In line 2, I suggest replacing "apply" by "extend".

## Results

p. 5, l. 3: (S) The phrase "The presence of multiple unique frequent haplotypes under a soft sweep..." is a bit unfortunate, although I think I know what you mean. How about "The presence of multiple unique haplotypes at high frequency under a soft sweep..."

p. 6, l. 5: (S) For consistency in usage of tense, I suggest saying "...then used an approximate..." rather than "...then use an approximate...". I did not catch this in the first round of review.

p. 9, l. 10: (C) I found the introduction of "haplotype" here confusing, because G123 is likely not responding to the third-most frequent haplotype, but likely to the two most frequent haplotypes (see also point 1.ii) by the second reviewer). I realise that "haplotype" makes sense if referring to H123 in this sentence, but not to G123 - unless I am missing something here. See my general concern above.

p. 15, l. 5–20: (C) I appreciate that runs of homozygosity (ROH) might be informative about past selection, but I found the new experiments introduced by the authors insufficient to learn much about these patterns. The new paragraph is not very illuminating as the analyses revealed no clear relationship between ROH length/abundance and the presence of a sweep. The strength and softness of a sweep might non-trivially affect the efficacy of recombination in generating very specific patterns of ROH and MLG statistics. Exploring these patterns seems worth an effort in the future, but it seems too early for conclusions. As mentioned above, I regret that the part on balancing selection has been sacrificed in favour of the ROH analyses.

## Discussion

p. 16, l. 6–8: (R) Please improve the formulation here. "Haplotype homozygosity" is a problematic term; I think you mean expected homozygosity.

p. 16, l. 31: (R) "strong sweep results" -> "strong-sweep results"; insert "the" before "selection coefficient"

p. 16, l. 32: (S) Insert "the" before "partial sweep" and "number of initially-selected haplotypes"

p. 17, l. 2: (R) "moderate selection [...] results" -> "moderate-selection [...] results"

p. 17, l. 17: (S) "under bottleneck" -> "under a bottleneck"; "or expansion" -> "or an expansion"

p. 17, l. 19: (C) The phrase "population size change experiment" is unfortunate.

p. 17, l. 28 – p. 18, l. 11: (S) This paragraph could be shortened.

p. 22, l. 9: (S) "consider" -> "considered"

p. 22, l. 19–20 (C) The term "human-inspired" reads strange here, although I know what you mean. Please reformulate.

p. 23, l. 1–5: (R) Please refer to Fig. S22.

p. 23, l. 17–25: (C, R) The interpretation of the admixture results made partially sense to me. However, I think it is important to recognise what "small" here means w.r.t. to the size of the donor population. It means small relative to the time between the population split (here: 4000 generations into the past) and the time of admixture (here: 200 generations ago), and small relative to the inverse of the mutation rate. I appreciate that the parameters chosen by the authors seem realistic for human populations, but not for a generic statement on the extent to which admixture could confound signals of soft sweeps. I also am not fully convinced that the confounding signal stems merely from an increased rate of coalescence in a small donor population (with N = 10^3), but that inter-population "hybrids" (i.e. heterozygotes) would contribute strongly to elevated MLG scores if the populations had diverged for long enough. I suggest that the authors refine their discussion. Along a similar line, it may be informative to indicate the split and admixture time in Fig. S21 not only in terms of generations, but also in terms of multiples of 2*N generations.


## Figures

Figure 6: (C) In the second-to-last line of the caption, I think it should say "G1/G2" instead of "G12".


## Supporting tables and figures

Figure 2S: (C) I think it should say H123 and G123 instead of H12 and G12 in the caption.

Figure S3: Same comment as for Figure S2.

Figure S4: (C) As mentioned above, it would be quite informative to introduce a patterning of the coloured bar sections that indicates whether that section represents a homozygous or heterozygous MLG.

Figure S9: (C, R) Panels B and D reveal a striking difference between H2/H1 and G2/G1 in terms of their probability density functions (PDFs). However, throughout the paper, a strong analogy is claimed between these to statistics. It would be nice if the authors could attempt to explain the bimodal PDF of G2/G1. I wonder if this has to do with the fact that homozygous *and* heterozygous haplotype pairs contribute to G2/G1.

Figure S20: (C) The term "expected homozygosity method" is problematic, as it refers to both the H and G statistics, the latter of which are not expected homozygosity statistics. See other comments above.
