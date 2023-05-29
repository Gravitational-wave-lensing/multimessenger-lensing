# multimessenger-lensing
A parent repository that holds submodules that are used in Utrecht-CUHK multimessenger lensing projects. 

**How to clone**: Either `git clone git@github.com:Gravitational-wave-lensing/multimessenger-lensing.git && git submodule update --init --recursive` or `git clone --recurse-submodules git@github.com:Gravitational-wave-lensing/multimessenger-lensing.git`

**Slack**: [link](https://join.slack.com/t/multimessengerlensing/shared_invite/zt-1w4bh5s42-V7O0WpTt3mFa1Lk2aEr2Dg) 

**Rules**: Keep it simple and documentation short. 

*Packages in alphabetical order (keep short):*\
**Golum**: Software for strong lensing parameter estimation with injections and real gravitational-wave data.\
*Example use-cases*: (1) Using two or more gravitational waves, estimate the Bayes factor and Odds ratio to quantify if the event is strongly lensed; (2) estimate the joint posterior distribution of N gravitational-wave images; (3) perform simulated parameter estimation with simulated, strongly lensed gravitational waves. \
*Dependencies*: Uses *LeR* to estimate the posterior Odds, the prior distribution of parameters, and draw injections. \
*Methodology*: https://arxiv.org/abs/2105.04536, https://arxiv.org/abs/2304.12148

**gwsnr**: Software for computing the signal-to-noise ratio (SNR) of a given binary system fast.\
*Example use-cases*: Compute the signal-to-noise ratio and pdet of a given binary compact object system.\
*Dependencies*: N/A

**LeR**: Software for statistical modeling of gravitational-wave lensing. \
*Example use-cases*: (1) Compute the rate of strong lensing for a given binary black hole population model and galaxy lens population model; (2) create strong lensing injections; (3) estimate the strong lensing prior Odds and produce a strong lensing prior for SL analyses.\
*Dependencies*: Uses gwsnr for fast signal-to-noise ratio (SNR) computation.


**Related publications (ArXiv year-ordered)**:

https://arxiv.org/abs/2304.12148 \
https://arxiv.org/abs/2205.11499 \
https://arxiv.org/abs/2204.08732 \
https://arxiv.org/abs/2110.06873 \
https://arxiv.org/abs/2106.06303 \
https://arxiv.org/abs/2105.04536 \
https://arxiv.org/abs/2004.13811
