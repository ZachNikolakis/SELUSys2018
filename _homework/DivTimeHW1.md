---
title: DivTime HW1
teaching: 180
exercises: 0
questions:
- "How does a estimating a solution using a Bayesian method differ from likelihood?"
- "How does the output of a Bayesian tree search differ from that of likelihood or parsimony?"
objectives:
- "Explain what different models are telling us about evolution."  
- "How does a heuristic search differ under likelihood?"
- "Perform ML analyses using PAUP on LONI" 
---

## DivTime HW1
1. When we describe the FBD as a mechanistic model, what does that mean? How does this contrast to node calibrations?
This is referring to incorporating extinct taxa in the tree and using one model for both extinct and extant. This differs from node-calibration techniques as these priors are set with the parameters of the suggested age being the at least minimum and some distribution chosen by the researcher (i.e., uniform, gamma, etc).
2. When we apply a node calibration, what are we trying to describe? 
We are attempting to describe the time in history at which one lineage split into two by constraining the given node with a fossil prior and some distribution. Sampling from the applied distribution gives the node age a confidence interval between dates.
 
