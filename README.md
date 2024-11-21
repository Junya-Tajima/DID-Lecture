# DID-Lecture

This repository contains the stata code for a lecture, entitled "Recent Discussions in Difference-in-Differences". It is designed for students and researchers who want to understand recent discussions on difference-in-differencs (DID) and implement recently developed methods using stata. 

---

## 📋 Covered Contents

- **1 Introduction to DID**: I explain the basic concepts of DID in the canonical case (2 periods, one group becomes treated in the second period, the other is never treated) and the conditions that should be satisfied to identify ATT (Avearge Treatment Effect on the Treated).
- **2 Staggered DID**: I explain the issues on DID involving staggered treatment timing and many periods and introduce alternative estimators.
- **3 DID and Time-Invariant Covariates**: I explain the concepts of Conditional Parallel Trends Asuumption and present sevaral methods to conduct DID estimation including time-invariant covariates. 
- **4 DID and Time-Varying Covariates**: I explain the problems in using two-way fixed effects estimator with time-varying covariates and assumptions that should be satisfied to identify ATT. 

---

## 🛠 Features

- Step-by-step tutorials for implementing DID analysis.
- Visualization techniques for interpreting results.
- Ready-to-use Python scripts and datasets.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Python installed along with the following libraries:

- `pandas`
- `numpy`
- `statsmodels`
- `matplotlib`
- `seaborn`

You can install these libraries with the following command:

```bash
pip install pandas numpy statsmodels matplotlib seaborn
