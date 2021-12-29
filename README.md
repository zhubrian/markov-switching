# regime-switching

**Context:**

Term paper for ECON 419 (Financial Time Series Econometrics) and fall semester component of the senior essay for the B.A. in Economics and Mathematics at Yale University

**Title:**

Regime-switching factor models for cryptocurrencies

**Abstract:**

In this paper, we consider a Markov regime-switching factor model with the goal of explaining
asset returns while considering cyclical patterns present in the market. To estimate the model’s
parameters, we formulate an expectation-maximization algorithm that only requires running
forward-backward procedures and linear regressions. The model and algorithm are empirically
tested on cryptocurrency data over the past year with a three-factor model. The results suggest
that a moderate number of regimes are optimal based on the Bayesian information criterion and
that our algorithm has desirable properties, while justifying the choice of factors and providing
another interpretation of explained asset returns via regime-dependent parameters.

**Paper:**

See https://github.com/zhubrian/regime-switching/blob/main/econ419-paper.pdf.

Data obtained from https://www.coingecko.com/en and https://home.treasury.gov/.
