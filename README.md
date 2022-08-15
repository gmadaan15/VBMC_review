# VBMC_review and its correlation with Policy Gradient based RL algorithm.
Variational Bayesian Monte Carlo and Noisy Likelihoods: A Review and some new suggestions : This report is a review of the paper Variational Bayesian Monte Carlo by Luigi Acerbi and of further extension of VBMC([1](https://github.com/lacerbi/vbmc), [2](https://github.com/lacerbi/infbench#references)) that addresses the limitations of the former paper by including noisy likelihoods. VBMC is an approximate inference method that combines Variational Inference with Bayesian Quadrature. We perform experiments as done in the original paper, compare with the benchmarks and provide our insights regarding them.

We find a very close correlation between VBMC and the routine procedure of Policy Gradient based RL algorithms. And looking at this correlation and the performance improvement of more Policy Gradient methods that use Natural Gradient ascent/descent instead of vanila Gradient ascent/descent, we suggest the same change in the VBMC algorithm. 
![alt text](https://github.com/gmadaan15/VBMC_review/blob/main/Correlation_2.png)
