# ABSN Stepped-Wedge Trial Resources

This repository contains simulation code and summary metrics for the **BCWC-Trauma** study.

## Key Resources & Citations

### 1. Adherence & Best Practices
* **Nevins et al. (2026)**: *Adherence to key recommendations for design and analysis of Stepped-Wedge Cluster Randomized Trials: A Review of trials published 2016-2022.* (Clinical Trials).
  * *Context:* This is the primary anchor for why we highlight design pitfalls and reporting standards.

### 2. Design Foundations
* **Hussey & Hughes (2007)**: *Design and analysis of stepped wedge cluster randomized trials.* (Contemporary Clinical Trials).
  * *Context:* The foundational model for our LMM simulation.

### 3. Small-Sample Methodology
* **Preisser et al. (PCORI)**: *Small-Sample Corrections for GEE in Cluster Randomized Trials.*
  * *Context:* Explains why "vanilla" GEE under-covers in our 8-cluster simulation and provides the technical fix.

### 4. Extensions (Survival & Heterogeneity)
* **Kasza et al. (2023)**: *Reporting of stepped wedge cluster randomised trials: A systematic review.* (Journal of Clinical Epidemiology).
* **Ryan, M. M. (2023)**: [GitHub Repository - SW Survival](https://github.com/maryryan)
  * *Context:* Useful for extending these simulations to time-to-event outcomes.

---
*Maintained by bmbadger*
