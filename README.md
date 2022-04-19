# learn-levy
Article code (ing)

"An end-to-end deep learning approach for extracting stochastic dynamical systems with α-stable Lévy noise"

python packages version:

numpy == 1.20.3;
pytorch == 1.9.0;
tensorflow == 2.5.0;
tensorflow-probability == 0.12.2

SDE:
dX_t = f(X_t)dt + g(X_t)dL_t^{\alpha}

File naming conventions:
dimension-Levy-(alpha value)-drift-diffusion

alpha estimation refers to "Parameter estimation of Alpha-Stable Distributions Based on MCMC" DOI: 10.1109/ICACC.2011.6016424


Karmers-Moyal method with memont generating function can be found in https://github.com/liyangnuaa/Extracting-stochastic-dynamical-systems-with-alpha--stable-L-evy-noise-from-data/tree/main.
