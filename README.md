# Economic Activity Forecasting: Puebla, Mexico

## Overview

This project analyzes and forecasts the quarterly Indicator of State Economic Activity (ITAEE) for Puebla, Mexico, using time series methods in R.

The analysis compares candidate ARIMA models and evaluates model selection criteria to obtain forecasts for the ten quarters following the last observation.

## Data

* **Region:** Puebla, Mexico
* **Frequency:** Quarterly
* **Sample period:** Q1 1980 – Q2 2025
* **Observations:** 181
* **Software:** R

## Methodology

1. Explored the time series and assessed stationarity.
2. Applied a Box-Cox transformation and first differencing.
3. Identified and treated an outlier associated with 2020 Q2.
4. Examined ACF and PACF plots to guide ARIMA specification.
5. Compared candidate models using AIC and BIC.
6. Selected a final model and generated forecasts for ten periods.

## Selected Model

The selected specification was ARIMA(0,1,1) with a Box-Cox transformation and drift.

## Tools

* R
* Time series analysis
* ARIMA modeling
* Stationarity testing
* AIC and BIC model selection

## Repository Contents

* `itaee_analysis.R`: analysis and forecasting code.
* `results/`: forecast visualization and model diagnostics.

## Notes

This is an academic econometrics project. Forecasts are model-based estimates and should not be interpreted as guaranteed future outcomes.

