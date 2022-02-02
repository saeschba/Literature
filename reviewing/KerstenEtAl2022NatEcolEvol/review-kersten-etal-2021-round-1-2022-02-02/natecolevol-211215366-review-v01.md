# Review of Manuscript NATECOLEVOL-211215366 by Kersten et al. "Standing genetic variation fuels rapid evolution of herbicide resistance in blackgrass"

## Publication criteria by Nat. Ecol. Evol.
- Present an advance in understanding likely to influence thinking in the field: [reinforcing the predominant view that ]
- Strong evidence for the conclusions: [moderate evidence, simulations indicate plausibility of conclusions drawn, but do not provide evidence compelling enough, no inferential framework used to support conclusion; expand; use statistics developed to differentiate between SSV and SDM, e.g. iHS or EHH (haplotype-based), or Tajima's D and Fay & Wu's H (SFS-based)]
- Discernible reason why the work deserves visibility of a Nature Portfolio journal rather than the best specialist journals: [yes, expand]

## Decisions
- [ ] Acceptance without editorial revisions
- [x] Invitation to revise before final decision
- [x] Reject with indication that further work might justify a resubmission
- [ ] Reject outright (reasons: specialist interest, lack of novelty, insufficient conceptual advance, major technical and/or interpretational problems)

## Summary
- Purpose: Understand the genetic basis and evolutionary processes underlying rapid adaptation
- System: Resistance to acetolactase synthase (ALS) and acetyl-CoA carboxuylase (ACCase) inhibiting herbicides in blackgrass (*Alopecurus myosuroides*), a major weed in cereal crops in the temperate climate zone including Europe
- Objectives:
    1. Infer the geographical structure and effective size of European blackgrass populations
    2. Explore the extent and nature of non-target site resistance (NTSR) to ACCase (it remains unclear to me why ALS resistance was not analysed --> ask) 
    3. Investigate the diversity, geographical distribution and evolutionary relationship of haplotypes harbouring target-site resistance (TSR) mutations at the ACCase and ALS genes
    4. Assess the extent to which TSR arose from standing genetic variation or as de-novo mutations
- Approaches:
    - De-novo assembly and annotation of a blackgrass reference genome based on PacBio long-read and Hi-C library DNA sequencing, as well as Illumina short-read and PacBio IsoSeq long-read RNA sequencing data.
    - Objective 1: SNPs called from ddRADseq data from 1,122 plants from 44 populations from nine European countries and three herbicide sensitive reference populations. PCA, Admixture, TreeMix, and Watterson's theta to estimate effective population size
    - Objective 2: Bulked-segregant analysis with two bulks formed of plants that were highly sensitive (dead) vs. quasi-insensitive to treatment with ACCase inhibiting herbicide; genome-scan for SNPs with statistically significant association with treatment response with BayPass.
    - Objective 3: PacBio long-read sequencing of ALS and ACCase amplicons, generation of haplotype networks, haplotype trees, and PCA, and identification of one or two putative copies of the ALS gene based on synonymous distances between paralogs and alignment of PacBio IsoSeq transcripts and GenBank sequences to the new assembly.
    - Objective 4: Qualitative analysis of haplotypes with TSR mutations, their phylogenetic and mutational distances, and their spatial distribution. Forward-simulations of the standing-variation and de-novo-mutation scenarios in isolated populations under an ACCase gene model.
- Main results:
    1. Population structure determined by geography (countries) to a weak extent only; a signal of admixture in multiple countries (BE, DE, FR, NL) in line with a polyphyletic status of plant individuals from individual countries.
    2. 
- Conclusions:
- Verdict:

## Major concerns

1. The authors assume a model of directional selection with dominance and let the dominance coefficient $h$ vary between 0 and 1 (i.e. complete dominance to complete recessivity of the derived allele, but no under- or overdominance) in the formulation of the theory. However, the authors then fix $h$ to 0.5 (no dominance) in their simulations and to 1 (complete recessivity) in their analyses of the derived TSHR allele in domestic chicken. While the latter decision is justified by empirical evidence, I wonder why the authors then did not also consider the case of $h = 1$ in their simulations. More generically, I think the authors should replicate a subset of their simulations for a range of $h$ values, including the extremes of $h=0$ and $h=1$. Allele frequency trajectories under these two extremes show qualitatively different dynamics, especially close to the boundaries of 0 and 1. Whether these differences can be discerned by the proposed inference approach, and how estimates of $h$ are confounded with estimate of the selection coefficient $s$ if of high interest, but remains unexplored. If simulations to address this question are too expensive, the authors should at least thoroughly discuss the potential impact of their choices of $h$ on their estimates of $s$ and the timing of selection.

2. The authors distinguish four alleles in their one-locus model, even though there are only two functionally different categories of alleles. The second axis of differentiation contrasts alleles within the same functional category by whether they are derived from the resident or the continental population. The necessity for this second axis of differentiation is not immediately obvious, but becomes implicitly clear as one reads the theory: it encodes essential information to disentangle the effects of gene flow and selection on the frequency of functional allele categories. As this seems to be an essential detail of the design of the approach, I suggest the authors explicitly motivate the choice of a four-allele rather than a two-allele model. Such a motivation might be placed around what are currently lines 75–77, or alternatively lines 116–118.

## Minor comments
**C:** comment; **Q:** question; **S:** suggestion; **R:** request.

### Generic
- Parts that I think should be written in past tense (methods, what the authors did) are currently written in present tense. Examples include "run" instead of "ran" in line 242, "re-analyse" instead of "re-analysed" in line 339, and "simulate" instead of "simulated" in line 445. I propose the authors revise this issue in the entire text.

### Introduction

- [l.34] **R:** Please clarify what exactly is the undesirable feature in aDNA. I suspect the authors want to say that high computational costs for large evolutionary timescales become a strong limitation for the analysis of aDNA. The formulation may need to be improved.

### Materials and Methods

- [l.99] **Q:** Is there a particular reason for why $s$ is scaled by $2N$, whereas $m$ is scaled by $4N$? I found this confusing. A corollary of the current choice of scaling is the factor of $1/2$ multiplying $\beta$ in Eq. (2), which could be omitted if $\beta(t)$ were defined as $2Nm$ rather than $4Nm$ (if $t \geq t_m$).
- [l.172] **S:** "Although it can be achieved by..." $\rightarrow$ "In principle, the transition probabilities can be obtained by..."
- [l.173–174] **S:** "...in Eq. (1) like Bollback et al. (2008) and He et al. (2020c), typically using a finite difference scheme, this requires..." $\rightarrow$ "...in Eq. (1) typically using a finite difference scheme (cf. Bollback et al. 2008;  He et al. 2020c). However, this requires..."
- [l.178] **S:** "...in this work that only involves..." $\rightarrow$ "...in this work. The PMMH algorithm only involves..."
- [l.220] **Q:** Should it not say ${x_{1:K}^{}}$ instead of ${x_{1:K}^{\ast}}$ on the RHS of the equation?

### Results
- [l264–267] **S:** ", thereby assuming that the continent allele counts of the sample are unavailable at first three and seven sampling time points, respectively, for each..." $\rightarrow$ ". To study the impact of missing continent allele counts, we assumed that he continent allele counts of the sample are unavailable for the first three or seven sampling time points for each...". **S:** Omit the parentheses surrounding "as shown [...] Figure 1".
- [l.296] **S:** "that" $\rightarrow$ "for which"
- [l.301] **C:** "degrades" sounds somewhat strange here. How about "dilutes" or "blurs"?
- [l.302–303] **Q:** Should the two specific values of $k_m$ not be reversed here, i.e. $k_m = 360$ first and $k_m = 90$ second, to agree with what is written in words?
- [l.321] **S:** "demonstrates" $\rightarrow$ "has"
- [l.368] **C:** The negative value for the time $k_m$ at which migration starts may confuse the reader. Perhaps remind them of time being measured relative to 0 BC (cf. Table 2, where an analogous footnote might be appropriate).

### Discussion

- [l.445] **S:** Omit "further"
- [l.467] **S:** No period after "developed"; "See" $\rightarrow$ "see"; place parentheses only around "2018" rather than the entire reference.

### Figures and Tables
- Fig. 4 & 5: **S:** In the captions, replace "aquamarine" and "coral" by "green" and "orange" to simplify?
- Table 3: **R:** Typeset minus signs appropriately, i.e. wider than the currently used en-dash.