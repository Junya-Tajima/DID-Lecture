# DID-Lecture

This repository contains the stata code for a lecture, entitled "Recent Discussions in Difference-in-Differences". It is designed for students and researchers who want to understand recent discussions on difference-in-differencs (DID) and implement recently developed methods using stata. 

##  Covered Contents

- **Introduction to DID**: I explain the basic concepts of DID in the canonical case (2 periods, one group becomes treated in the second period, the other is never treated) and the conditions that should be satisfied to identify ATT (Avearge Treatment Effect on the Treated).
- **Staggered DID**: I explain the issues on DID involving staggered treatment timing and many periods and introduce alternative estimators.
- **DID and Covariates**: I explain the concepts of Conditional Parallel Trends Asuumption and present sevaral methods to conduct DID estimation including time-invariant / time-varying covariates. 
- **Synthetic DID**: I review the properties of Synthetic DID and apply this method to the actual data.
- **DID and Sensitivity Analysis**: I explain some disadvantages of conventional pre-trend tests and review some sensitivity analyses which is developed recently. 

##  Features

- Advanced lectures for second-year master's students in economics. 
- Students are expected to already have a solid understanding of econometrics and causal inference.
- Ready-to-use Stata code and datasets.

## Prerequisites

You need these packages to run do-files:

- `reghdfe`
- `ftools`
- `event_plot`
- `addplot`
- `drdid`
- `csdid`
- `bacondecomp`
- `egenmore`
- `sdid`
- `sdid_event`
- `honestdid`

You can install these packages with the following command:

```bash
*Install packages
ssc install reghfe
ssc install ftools
ssc install event_plot
ssc install addplot
ssc install drdid
ssc install csdid
ssc install bacondecomp
ssc install egenmore
ssc install sdid
ssc install sdid_event
ssc install honestdid

