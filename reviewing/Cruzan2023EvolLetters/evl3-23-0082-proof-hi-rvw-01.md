---
title: Review of Manuscript EVL3-23-0082 by Cruzan: "Testing Wright's Intermediate Population Size Hypothesis – When Genetic Drift is a Good Thing"
author: Simon Aeschbacher
date: 28 August 2023
geometry: "left=3cm,right=3cm,top=2.5cm,bottom=2.5cm"
output: pdf_document
linestretch: 1.15
---

## Summary
In this manuscript, Cruzan aims to find a mechanistic explanation for the arguably accumulating evidence of rapid (adaptive) evolution following population bottlenecks. To this aim, the author sets out to test if genetic drift can "facilitate" selection in "small" populations by means of simulation and comparison of these to existing theoretical predictions based on the diffusion approximation. Cruzan claims to find evidence for "drift facilitation" in terms of increased changes in the frequency of weakly beneficial, initially rare, alleles in small (here: $N < 100$) populations. He further interprets quantitative differences between simulated fixation times and those predicted by the diffusion approximation as qualitative evidence that genetic drift accelerates adaptive evolution in small, and decelerates it in large, populations. This interpretation implies that the diffusion approximation fails to appropriately capture the interaction between genetic drift and selection beyond quantitative approximation errors. Cruzan also simulates what he calls "fixation flux" – or what is more commonly known as the rate of substitution – of beneficial mutations to apparently find that this rate declines with increasing population size. Even though the authors seems to acknowledge that this finding is affected by too short a simulation time, he concludes that the substitution rate of beneficial mutations is lower in large compared to small populations – and thus that large populations are more liable to accumulate segregation load compared to smaller ones. Cruzan's dissection of genetic load into drift load and segregation load as a function of population size is an interesting one, but the conclusion that differences in these types of load between small and large populations explain rapid adaptation following population bottlenecks remains little more than a speculation given the narrow scope of the simulations performed.

I am afraid that the manuscript is unclear with respect to fundamental points, including what exactly is to be understood by "small" (and "intermediate") population size, what exactly is meant by "drift facilitation" and how it should be measured properly, and why the author is challenging the diffusion approximation when the analyses he performs are – by their design – not capable of proofing its qualitative "wrongness".

Moreover, the effects on simulation outcomes of implementation choices such as the distribution of selection coefficients or the way in which an individual's fitness arises from fitness functions at individual loci on simulations remain unclear.

I have also read the reviews of three previous reviewers and the response to these by the author. Reviewer 1 raised substantial concerns based on their expert background in theoretical results by Wright, Haldane, Kimura and Ohta relevant to the scope of Cruzan's manuscript. I share these and am thus not going to repeat them, even though I do not think they have been substantially attenuated by the author's response to them.

Overall, I think this manuscript suffers from too many conceptual issues and makes claims not backed by the analyses. The manuscript cannot be published in Evolution Letters as it is. It would take substantial conceptual redesign, an extension in the scope of simulations, and a thorough comparison to theoretical results not yet integrated. I am afraid the only recommendation I can suggest is to reject the manuscript.

## Major concerns

1. Even though written well overall, the manuscript suffers from a lack of clarity about fundamental points:
    1. The author at times refers to "small" populations (e.g. l.45), "intermediate" populations (e.g. l.297), or "intermediate sizes (small)" populations (l.97) as the populations of interest. I acknowledge that some of this terminological inconsistency follows from what Wright, Simpson and the author himself deem to be the size range of interest. However, it would then even more so seem important to clearly delineate which range of population sizes is of interest.
    2. A related issue is that population size can be defined in absolute terms (no. of individuals $N$) or relative to the strength of evolutionary processes (e.g. relative to the selection coefficient [$1/(4s)$] or the mutation rate [$1/(4u)$]). An intricate problem here is that Wright, Kimura, Ohta, Ewens and others would tend to use the relative definition, acknowledging the fundamental result from the diffusion approximation that it is the compound parameters (e.g. $Ns$, $Nu$, ...) that determine the dynamics and equilibria of gene frequencies. The author, however, seems to be making the case that this "diffusion view" fails to capture a fundamental and qualitative aspect of how drift ($N$) interacts with selection ($s$) beyond $Ns$. For that reason, the author must at times refer to the absolute definition, but this requires a "translation" to the relative definition at times when it comes to comparing his claims to the theoretical predictions based on the diffusion approximation. This issue leads to a confusion that hampers both reading flow and comprehension of the manuscript. .
2. I am concerned about a major mismatch between the overarching aim of the manuscript - to understand why rapid 

## Minor comments
**C:** comment; **Q:** question; **S:** suggestion; **R:** request.

### Abstract
- ...

### Introduction
- [l.xx–xx] ...