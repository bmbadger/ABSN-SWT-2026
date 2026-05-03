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

### REFERENCES

* **Hussey MA, Hughes JP.** Design and analysis of stepped wedge cluster randomized trials. *Contemp Clin Trials.* 2007;28(2):182-191.
* **Kasza J, et al.** Reporting of stepped wedge cluster randomised trials: a systematic review. *J Clin Epidemiol.* 2023;157:11-21.
* **Li F, Wang B, Heagerty PJ.** What is a stepped-wedge cluster randomized trial? *JAMA Intern Med.* 2025;185(5):593-594.
* **Nevins P, Ryan MM, et al.** Adherence to key recommendations for design and analysis of Stepped-Wedge Cluster Randomized Trials: A Review of trials published 2016-2022. *Clinical Trials.* 2026.
* **Preisser JS, et al.** Review of small sample corrections for generalized estimating equations in stepped wedge cluster randomized trials. *PCORI Methodology Report.*
* **Ryan MM.** *StepWedgeSurvival: Tools for power analysis and simulation in SW-CRTs with time-to-event outcomes.* GitHub. 2023. [https://github.com/maryryan](https://github.com/maryryan)
