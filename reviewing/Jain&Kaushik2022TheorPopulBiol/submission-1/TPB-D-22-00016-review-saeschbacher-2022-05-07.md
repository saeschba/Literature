# Review of Manuscript TPB-D-22-00016 by Simon Aeschbacher

## Summary

Abbreviations to be introduced:
- site-frequency spectrum (SFS)

## Major comments

1. The distinction between "time-averaged SFS" and "equilibrium SFS" could be made more clear. I suggest the authors be more explicit about the contexts they refer to when they use these two terms. The reason is that the manuscript considers a range of scenarios in which at least one aspect of the environment (selection or demography) is dynamic, and thus in which "time-averaged" makes sense. On the other hand, "equilibrium" may refer to the fully constant scenario (constant population size, constant selection), but technically also to an equilibrium of a fast process relative to a slow process in those cases where a separation of time scales is assumed. For specific cases, see "Minor comments" below.
2. There might be a confusion between "difference in phase" and "difference in period". My impression is that the assumption of "no difference in periods" between the dynamics of selection and demography is sometimes also referred to as a situation of "no difference in phase" between selection and demography. If I understood the formulation of the model correctly, there is no explicit parameter expressing a phase difference. I suggest that the authors either refrain from using "phase difference" and only write about "difference in period", or that they extend either eq. (3) or (4) to include "$t + \tau$" instead of $t$ on the RHS, respectively, where $\tau$ is the phase difference. My impression is that the former solution is more appropriate, as the latter one might complicate the scope of the current manuscript. However, I might be missing an obvious connection between phase and period not made explicit in the manuscript.
3. In the Discussion I missed a paragraph on limitations and crucial assumptions of the work presented here. In connection with this point, I also missed a more comprehensive outlook of what future work should address next in the view of the authors.

## Minor comments

I use the following abbreviations to qualify my comments:
- **C:** Comment
- **Q:** Question
- **R:** Requested change
- **S:** Suggestion

### Abstract
- l.6: **S:** Split a long sentence: "...theory approach, and derive..." --> "...theory approach. We derive..."
- l.8–10: **C:** This sentence is not entirely clear, partially because the context to which "equilibrium SFS" refers to is not explicitly given. The reader might misinterpret the context as "when the population experiences both positive and negative cycles of the selection coefficient", but the quoted part does not describe the context under which the equilibrium exists, but the condition under which there is a significant difference to the time-averaged SFS. Clarity in this sentence seems crucial, as it summarises the essence of the manuscript. **S:** If I understood correctly, it would be preferable to write "We show that, for strong selection and a slowly changing environment, and assuming that the population experiences both positive and negative cycles of the selection coefficient, the SFS differs significantly from the equilibrium SFS in a constant environment." Note: I suggest to omit "non(-)equilibrium" because even in a constant environment the SFS may deviate from the equilibrium SFS before the equilibrium is reached (e.g. after a perturbation). One might use "time-averaged" instead of "non-equilibrium", but doing so anticipates the specification of the focus of the paper given at the very end of the Introduction on page 5.

### 1 Introduction
Page 3
- l.17: **S:** "The above discussion assumes..." --> "The extensions of the classical results above assume..."
- l.19–20: **S:** To increase clarity: "...there is no stationary state and the nonequilibrium SFS can differ significantly from the equilibrium one..." --> "there is no stationary state and the time-averaged SFS in a changing environment can differ significantly from the equilibrium SFS in a constant environment".
- l.23: **R:** Insert "a" after "while"; "low frequency" --> "low-frequency".

Page 4
- l.19: **R:**: "...time scales also for which different..." --> "...time scales also, for which different..."
- l.23: **S:** To improve the transition and be more explicit about the gap of knowledge addressed: "Motivated by the above discussion, here we..." --> "To better understand the dynamics of the SFS in populations of varying size and in changing environments, here we..."

Page 5
- l.4: **S:** To increase clarity: "...how the time-averaged SFS deviates from the equilibrium SFS" --> "...how the time-averaged SFS in a changing environment deviates from the equilibrium SFS in a constant environment".

### 2 Model

Page 6
- l.9–10: **C/Q:** This last part of the sentence could be understood as saying that the condition $0 \le \nu \lt 1$ ensures deterministic dynamics. I do not see how this is the case, but I might be missing something. I suggest the authors double-check the formulation.

### 3 Site frequency spectrum: diffusion theory

Page 7
- l.2–3: **S:** "...earlier work [...], using which we find that..." --> "...earlier work [...], from which we find that...". Also, there should be a full stop after Eq. (5).
- l.13: **C:** Avoid parenthesis within parenthesis in the citations.

Page 8
- l.2: **C/S:** "handle" may not be the best choice here. Perhaps use "solve" or "gain insight from"?

### Results

Page 9
- l.2: **C:** If I am not mistaken, by "static environment" the authors refer to both a constant selective environment ($s(t) = \bar{s}$) as well as a constant population size ($N(t) = \bar{N}$). It may be useful to state this explicitly once.
- l.3–5: **R:** "...SFS is known for a long time..." --> "...SFS has been known for a long time..." **C:** It is unclear what is meant by "its [N.B.: not it's] expression is not transparent". Does this mean that the derivation of these expressions is not clear in previous work? Or that the obtained expressions are (more) complicated (than necessary)?. The part "and simple analytical approximations have not been obtained, and therefore, we first discuss these below." reads a bit strange, because the simple analytical expressions first need to be derived before they can be discussed. **S:** I propose to revise this sentence completely, but I am lacking sufficient insight to make an appropriate suggestion.

Page 12
- l.19–20: **S:** Insert an article "a" before "beneficial mutant" and "deleterious one", respectively.

Page 13
- l.9: **R:** Insert "the" before "SFS". **S:** "...in slowly changing environments" --> "...in a slowly changing environment".
- l.17: **S:** I found the use of $\psi^{\prime}$ for $\Omega t$ problematic, because the prime might imply a derivative. I suggest to use $\Psi$ (uppercase 'Psi') instead of $\psi^{\prime}$, which would nicely run parallel to the use of $\omega$ and $\Omega$ as periods for the dynamics of selection and demography, respectively.

Page 14
- l.1: **S:** Insert the article "a" before "slowly changing environment".
- l.12: **R:** "these behavior" --> "this behavior"
- l.20: **C/S:** Notation: I suggest to use $\tau$ instead of $t^{\prime}$ to avoid confusion with derivatives in the definition of $\bar{f}(x)$.

Page 17
- l.10: **R:** Insert a comma between "times" and "which, because "which" is of a descriptive (not a defining) nature with respect to "heterozygosity".
- l.14–17: **C/S:** The wording used to describe effects on the SFS sounds suboptimal to me. What does it mean if the SFS is 'reduced' or 'enhanced'? How meaningful are these terms after normalisation of the SFS, which would likely be done in practice? I think the interest is more in how the *shape* of the SFS changes. In the present context, it might be more meaningful to refer to a 'positive contribution' and a 'negative contribution' to the SFS.
- l.21: **R:** Insert "the" between "both" and "positive"

Page 18
- l.1: **Q:** I wondered why the starting point for obtaining approximation (25) for strong, on-average zero selection is eq. (22) and not eq. (21). Equation (22) makes two additional assumptions compared to eq. (21), namely that $\omega = \Omega$ and that selection is strong so that its contribution can be ignored if $s(t) < 0$. To me, it was not obvious why these two assumptions would be carried over to the case of on-average zero selection, i.e. from subsection 4.2.3 to subsection 4.2.4. **S:** "get" --> "obtain". Part of my confusion might be due to the fact that, according to my understanding, no difference in period is not equivalent to no difference in phase.
- l.3: **Q:** Should it indeed say $\omega$ and not $\Omega$ in $\rho_{\pm}(t) = 1 \pm \nu \sin(\omega t)$? My understanding is that $\rho$ expresses the size of the population relative to the temporal average size, and that the size of the population cycles with period $\Omega$, not $\omega$. I might be missing an assumption about the relationship between the periods $\Omega$ and $\omega$.

Page 19
- l.12: **Q:** As for l.1 on page 18, I wonder why the starting point for eq. (27) is eq. (22) and not eq. (21). I might be missing assumptions in place about the periods $\Omega$ and $\omega$, and about the nature of selection if $s(t) < 0$.

Page 20
- l.6: **S:** "The above discussion thus demonstrates..." --> "The above considerations thus demonstrate...".
- l.6–11: **R:** Insert an article "a" before "slowly changing". **S:** I suggest to be more explicit about when exactly the heterozygosity in a slowly changing environment can be equal to that in a constant neutral environment. Since the sentence then becomes too long, I also suggest to split it into two. Specifically: "Figure 5a summarizes the results obtained above, and shows that for strong selection, the time-averaged mean heterozygosity in slowly changing environment is smaller than that in the constant environment with population size $\bar{N}$ and constant, positive selection coefficient $\sigma$ but it can be equal to that in the constant neutral environment." --> "Figure 5a summarizes the results obtained above, and shows that for strong selection, the time-averaged mean heterozygosity in a slowly changing environment is in general smaller than that in the constant environment with population size $\bar{N}$ and constant, positive selection coefficient $\sigma$. However, the time-averaged mean heterozygosity in a slowly changing environment can be equal to that in the constant neutral environment if there is no dominance ($h = 1/2$) and no phase difference between selection and demography." As stated above, I am confused about whether the authors use "no difference in period" as being equivalent to "no difference in phase", and if so, I might miss that these expressions do indeed mean the same.

Page 24
- l.9: **R:** Insert an article "a" between "for" and "weakly".
- l.11: **R:** Insert an article "a" between "for" and "weakly".
- l.14: **S:** "...results, and yield..." --> "...results, which yields..."
- l.18: **S:** "...given by the expression (14a) in the constant..." --> "...given by expression (14a) for a constant..."

### 5 Discussion

Page 27
- l.2: **R:** Insert an article "a" between "how" and "changing".
- l.15–20: **S:** I suggest to split this long sentence into two, to move the comma from between "size" and "$N_e$" to between "environment" and "but", and to omit the double-parentheses at the very end. Specifically, "We find that the effect of demography is mainly seen when the population size changes rapidly where the time-averaged statistical quantities behave the same way as in the constant environment but with reduced population size, $N_e$ given by the harmonic mean of the changing population size over a period (see (33))" --> "We find that the effect of demography is mainly seen when the population size changes rapidly. In this case, the time-averaged statistical quantities behave the same way as in the constant environment, but with reduced population size $N_e$ given by the harmonic mean of the changing population size over a period (see eq. 33)".

Page 28
- l.7: **R:** Insert an article "a" between "for" and "positively" and between "in" and "constant".
- l.16: **R:** Insert an article "a" between "in" and "changing".
- l.18–19: **S:** "...when it’s mutation rate relative to the frequency of change in the population size is small..." --> "...when the mutation rate is small relative to the frequency of change in the population size..."
- l.22–24: **C:** The following part remains unclear: "...the census population size in slowly changing, selective environment can also be interpreted as an effective population size, $N_e$". If I understood correctly, the census population size as such cannot be interpreted as an effective size, but one can compute the effective size as a function of the census size. There should be an article "a" between "in" and "slowly".

Page 29
- l.1: **R:** Insert an article "a" between "in" and "slowly".
- l.4: **R:** Insert an article "a" between "in" and "constant".
- l.7: **S:** "...high frequency variants..." --> "...high-frequency variants..."
- l.12: **R:** "...a SFS similar to that as in constant,..." --> "...an SFS similar to that in a constant,...".
- l.14–16: **S:** "Fig. 7 further shows that the time-averaged heterozygosity follows the same qualitative trend with dominance coefficient as for positively selected mutant in constant environment (see Fig. 1c)" --> "Fig. 7 further shows that the time-averaged heterozygosity shows the same qualitative dependence on the dominance coefficient as for a positively selected mutant in a constant environment (see Fig. 1c)".
- l.23: **R:** Insert an article "a" between "that" and "changing".

Page 30
- l.1–6 **S:** I suggest multiple changes in this sentence as follows: "...and deleterious mutations which leads to different levels of neutral heterozygosity at a linked site due to beneficial and deleterious sweeps, and that the neutral heterozygosity is strongly affected due to the deleterious sweeps even when the selection is changing slowly while the beneficial sweeps are not much impacted..." --> "...and deleterious mutations, which leads to different levels of neutral heterozygosity at sites linked to beneficial vs. deleterious sweeps. We have also shown that the neutral heterozygosity is strongly affected by deleterious sweeps even when selection is changing slowly, while the footprint of beneficial sweeps is not much impacted...". **C:** Most readers might associate 'sweep' with linkage to a beneficial allele; the term 'deleterious sweep' might be problematic.
- l.6–13: **C/S:** This sentence is too long and hard to read. Suggestion: "In this article, the fundamental quantity of interest is the mean absorption time and the key effect is that as a newborn mutant is more likely to be lost when selection is negative than when it is positive, and in a slowly changing environment, the contribution to polymorphism will come only from the part of the cycle when the selection is strongly positive, the time-averaged quantities will be quantitatively different from those due to positively selected mutants in constant environment." --> "In this article, the fundamental quantity of interest is the mean absorption time. The key effect is that as a de novo mutation is more likely to be lost if selection is negative than if it is positive. In a slowly changing environment, the contribution to polymorphism will therefore come only from the part of the cycle when selection is strongly positive, and the time-averaged quantities will be quantitatively different from those due to positively selected mutants in a constant environment.".
- l.19: **S:** Suggest a comma after "scenarios" and after "(Barton, 2000)".