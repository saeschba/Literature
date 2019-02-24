# Review of manuscript MEC-19-0061 by Matthey-Doret & Whitlock


## Summary

## Confidential comments to the editor


## TODO

- Fix Fst notation. Fst -> $F_\mathrm{ST}_$; dXY -> $d_\mathrm{XY}_$; Hs -> $H_\mathrm{S}_$


## Major issues

**X.** For the Fst outlier tests, the authors implemented a variant of FDist2, which assumes an island model of migration at equilibrium to produce the distribution of Fst under the null hypothesis of no BGS.
TODO(Simon): Go on here. Ask over which simulations the average Fst was calculated to obtain m. Ask how the deviations from the expected false positive rate can be explained.


**X.** Critisise the fact that results that do not support the main argument of the paper are somewhat arbitrarilly moved to the SI. This holds for the CN97 treatment in the case of both the dynamics of Fst, dXY, and Hs as well as the false positive rate (compare Figures XX and XX to Figures S2 and S4). And it holds for the No Recombination and No Migration scenarios in the case of the dynamics of Fst, dXY, and Hs (compare Figure XX and Figure S2) and the false positive rate (compare Figure XX and Figure S4), respectively.

**X.** Appendix A should be revised.

## Minor comments

C: Comment
Q: Question
S: Suggested change
R: Requested change


### Introduction


### Methods

- [l. 180--181] C: Here you say that in the flanking regions you only tracked (simulated) exons, but in lines 196 to 199 you say that in the case of the human genetic map you also simulated selection at regulatory sites. Please clarify.

- [l. 209--210] C: If 2% of the mutations are lethal ($s = 1$) and the average deleterious selection coefficient for the non-lethal mutations is 0.07, then the overall average would seem to be $0.02 \times 1 + 0.98 \times 0.07 = 0.0886$. The result is close to but not identical to the "mean heterozygous selection coefficient" of 0.1 reported in Table 1. Please clarify.

### Results

- [l. 424--425] S: Please discuss why the false positive rate is far from the $\alpha$ value in the No Migration treatment. I suspect that this is because the way $m$ is identified for the Fdist2 simulations is not appropriate. I have raised this issue before, and I think it is particularly evident in the case of no migration. Estimating a migration rate in a model of complete isolation under the assumption of an equilibrium between drift and migration will result in a 

### Discussion

- [l. 500] S: "yield to" $\rightarrow$ "yield"

### References


### Figures and tables

- [Fig. 2] S: As the authors mention in the main text, it is difficult to see when the 95% confidence intervals for the neutral and BGS scenarios overlap and when they do not. I wonder if the authors could add an asterisk or similar in cases of no overlap (as in Figure 4). R: Please fix the reference to the supporting figure (should be Figure S2 instead of Figure S3).

### Appendix A

- [Paragraph 2] R: Please fix the grammar in the first sentence ("simulations which results are"). C: The second sentence is confusing, as Figures A1 and A2 are arranged vertically (in fact, as separate figures), but referred to as "left" and "right" parts apparently.
-


### Supporting material

- [Fig. S2] R: In the caption, "means" $\rightarrow$ "mean". S: Please improve the ratio of figure content to annotation. Labels of panel rows and columns, axis label, and legend text are too heterogeneous in size and rather large compared to the plotting area, which makes it hard to digest the information. Reduce the number of font types in the mix. Please fix the reference to the figure in the main text (should be Figure 2 instead of Figure 1). S: Perhaps avoid the expression "Human treatment" (compare to "Human genetic map" in the main text).


## Points to return to

- Exclusion of sites with a MAF lower than 0.05. See response of authors, which basically says that they did it because everyone does it. The latter does not mean it is always the right thing to do. Is it understood why applying the MAF filter has as strong an impact as shown in Figure S3?
