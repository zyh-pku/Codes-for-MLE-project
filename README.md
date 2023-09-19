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
Heston_MIMLE_I_M_expansion_coefficients.m documents the closed-form formulae of the expansion coefficients of the Fisher information matrix for the marginal-information MLE under the Heston model.

## Figures and Tables for illustrations of our inferential theories
The following results show the information loss between the full-information MLE and the marginal-information MLE. Both the finite-sample and asymptotic distributions for two kinds of MLEs demonstrate the information loss. The visualized fit between the two distributions supports our inferential theories based on the long-span asymptotic property and the approximation
for Fisher information.
### 1. The explicit information loss under the BOU model
![ead991ab3b60e9a4c6922865e71382f](https://github.com/zyh-pku/Inference-in-Continuous-Time-Diffusion-Model-with-Latent-Variables/assets/145367171/8c057ac4-6bb7-4e7b-9037-f63aebe18288)
### 2. The visualized fit between finite-sample and asymptotic distributions for two kinds of MLEs under the BOU model as well as the Heston model
![4eaf0f82502ba688bb2e8f37a461eed](https://github.com/zyh-pku/Inference-in-Continuous-Time-Diffusion-Model-with-Latent-Variables/assets/145367171/9f60ea20-bc88-4ed8-84c0-c64c65069109)
### 3. The statistics for the finite-sample and asymptotic distributions for two kinds of MLEs under the BOU model as well as the Heston model
![976a9ddfb14d0145b1ddc0378675114](https://github.com/zyh-pku/Inference-in-Continuous-Time-Diffusion-Model-with-Latent-Variables/assets/145367171/ded89add-4970-4ba5-b7b6-4a0d2ec9c52c)
