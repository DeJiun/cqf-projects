# CQF Projects

## 1. Portfolio Optimisation & Risk Sensitivity
Derived Markowitz mean-variance optimal weights analytically from the Lagrangian 
closed form. Computed marginal VaR and ES sensitivities at 99% confidence to 
identify the dominant tail-risk contributor in a 4-asset portfolio.

## 2. Monte Carlo Option Pricing
Priced European vanilla and binary calls under three SDE schemes (Euler-Maruyama, 
Milstein, exact GBM). Conducted convergence analysis and demonstrated variance 
reduction via antithetic variates.

## 3. ML-Based Return Prediction
Engineered technical features from OHLCV data; applied a three-stage funnelling 
pipeline (correlation filter → RFECV → embedded selection) to train an XGBoost 
classifier with time-series cross-validation.
