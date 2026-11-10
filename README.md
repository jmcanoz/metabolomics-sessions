# Metabolomics data analysis sessions

Slides from two sessions I gave at the Metabolomics Unit of HUMV-IDIVAL (Santander, Spain) in November 2026. The slides are in Spanish.

- [Normalization, transformation and univariate analysis with real data](slides/20261106_normalization-univariate.pdf) (6 Nov)
- [Multivariate analysis and model validation](slides/20261110_multivariate-validation.pdf) (10 Nov)

The first one goes through a real COPD study from start to finish: quality control, normalization, PCA, volcano plots and FDR, and how to tell disease signal apart from drugs or smoking.

The second one uses a toy example with six people and five compounds, so every calculation can be done by hand. The main point is validation: the PLS-DA model gets R² = 0.77 on the data it was fitted on, but drops to Q² = 0.53 under cross-validation.
