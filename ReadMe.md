Forecasting Canadian Crop Production (1965–2020)
Overview

This project develops a statistically robust time-series forecasting framework to model long-term Canadian crop production trends under structural growth and climate variability.

Using historical production data from 1965–2020, the analysis applies stationarity testing, ARIMA modeling, and residual diagnostics to generate interpretable and policy-relevant forecasts.

The goal is not only predictive accuracy, but also model transparency and reliability for agricultural planning contexts.

Problem Statement

Canadian crop production exhibits long-term growth and volatility influenced by climatic shifts, technological improvements, and market forces. Raw time-series data is non-stationary, making naïve forecasting approaches unreliable.

The challenge was to:

Identify and correct non-stationarity

Build a statistically valid forecasting model

Validate assumptions using diagnostic testing

Communicate uncertainty for policy-level decision-making

Methodology
1. Exploratory Time-Series Analysis

Visual inspection of long-term trends

Autocorrelation and partial autocorrelation analysis

2. Stationarity Testing

Augmented Dickey-Fuller (ADF) test

Result: p-value = 0.84 → non-stationary series

Applied first-order differencing to stabilize mean behavior

3. Model Development

Evaluated ARIMA configurations

Selected ARIMA(2,1,2) based on AIC/BIC criteria

4. Model Diagnostics

Ljung-Box test → No significant residual autocorrelation

Jarque-Bera test → Residuals approximately normal

Residual plots confirmed randomness and lack of structure

5. Forecast Evaluation

RMSE: ~11.6 million units

MAPE: ~10.3%

A ~10% MAPE is considered acceptable in agricultural forecasting due to inherent climatic uncertainty.

Key Results

Successfully transformed non-stationary data into a stable modeling framework.

Generated 5-step ahead forecasts with confidence intervals.

Produced probabilistic projections to support risk-aware agricultural planning.

Demonstrated the importance of residual diagnostics for model trustworthiness.

Why This Matters

Agricultural forecasting is inherently uncertain, especially under climate volatility. This project emphasizes:

Robust statistical foundations

Transparent modeling assumptions

Interpretability over unnecessary complexity

Communication of uncertainty rather than point predictions

Forecasts should function as a compass for planning — not a guarantee.

Tech Stack

Python

pandas

numpy

statsmodels

matplotlib

seaborn

Future Improvements

Incorporate exogenous climate variables (ARIMAX)

Explore ensemble forecasting approaches

Implement rolling cross-validation

Compare against machine learning regressors

Author

Jazi Joseph
Data Science | Agricultural Analytics | Development-Focused Modeling