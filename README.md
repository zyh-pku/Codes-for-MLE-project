# Inference-in-Continuous-Time-Diffusion-Model-with-Latent-Variables

MIMLE_asymptotics_notebook_20230919.nb collects the closed-form formulas of the statistics as well as the information-theoretical quantities in the main paper and the online appendix.

## Examples for illustrations of our inferential theories
The folder Formulas_Results documents several examples.
### 1. The Bivariate Ornstein-Uhlenbeck (BOU) model -- Example of the Stochastic Drift (SD) model
BOU_MIMLE_stationary_Gaussian_covariance_matrix documents the covariance matrix of the stationary distribution of the filtering process, which is a Gaussian distribution with zero means.\
\
BOU_MIMLE_Fisher_information_diagonal_block.m documents the closed-form formulae of the diagonal entries of the Fisher information matrix for the marginal-information maximum likelihood estimator (MLE) under the BOU model.\
\
BOU_MIMLE_Fisher_information_off-diagonal_block.m documents the closed-form formulae of the off-diagonal entries of the Fisher information matrix for the marginal-information MLE under the BOU model.\
\
BOU_FIMLE_Fisher_information.m documents the closed-form formula of the Fisher information matrix for the full-information MLE under the BOU model.
### 2. The Heston model -- Example of the Stochastic Volatility (SV) model
Heston_MIMLE_I_M_expansion_coefficients.m documents the closed-form formulae of the expansion coefficients of the Fisher information matrix for the marginal-information MLE under the Heston model.\
