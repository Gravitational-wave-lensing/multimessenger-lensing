# multimessenger-lensing
A parent repository that holds submodules that are used in Utrecht-CUHK multimessenger lensing projects. 

Packages in alphabetical order (keep short):

gwsnr: Software for computing the signal-to-noise ratio (SNR) of a given binary system fast.
Example use-cases: Compute the signal-to-noise ratio and pdet of a given binary compact object system.
Dependencies: N/A

LeR: Software for statistical modeling of gravitational-wave lensing. 
Example use-cases: (1) Compute the rate of strong lensing for a given binary black hole population model and galaxy lens population model; (2) create strong lensing injections; (3) estimate the strong lensing posterior Odds.
Dependencies: Uses gwsnr for fast signal-to-noise ratio (SNR) computation.

