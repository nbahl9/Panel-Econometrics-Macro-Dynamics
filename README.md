# Multi-Variable Panel Econometrics: Macro Labor Dynamics & Well-being

This repository contains a quantitative macro research project analyzing structural cross-country panel data configurations using applied econometrics frameworks in Python.

### 📊 Econometric Methodology Implemented:
* **Pooled OLS Baseline Specification:** Evaluated multi-variable behavioral parameters utilizing Heteroskedasticity-Robust Standard Errors (`HC1` White estimator) to mirror STATA outputs exactly.
* **Cross-Product Interaction Architectures:** Modeled non-linear transmission mechanisms isolating how micro-level labor disruptions interact against macro country-level cultural indicators (`country_work_ethic`).
* **Entity Fixed Effects (FE) Transformations:** Implemented Within-Transformation (Demeaning) architectures utilizing MultiIndex clustering to absorb unobserved individual time-invariant heterogeneity (`respid`), tracking parameters across dynamic `year` structures.

### 🐍 Technical Architecture & Libraries:
* **Pandas & NumPy:** High-performance multi-index panel manipulation and categorical variable factor expansions.
* **Statsmodels & Linearmodels:** Advanced quantitative frameworks implementing `OLS` and `PanelOLS` variance-covariance engines.
* **Matplotlib:** Graphical cross-asset distribution plots.
