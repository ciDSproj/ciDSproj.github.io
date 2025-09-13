---
title: "CO2 Forecasting with Time Series"
excerpt: "In this project I built a seasonal ARIMA model to produce one-step ahead, dynamic and future forecasts for CO2 atmospheric concentrations.<br/>"

collection: machinelearning
---

This analysis focuses on CO2 atmospheric concentrations dataset. It covers data preparation and exploration using visualization and STL decomposition, checking stationarity by applying the Dickey-Fuller test and computing and plotting the ACF and PACF values.
<br/>

[GitHub](https://github.com/ciDSproj/timeseries_forecast)

---


Using grid search were identified the best parameters for building a seasonal ARIMA model. The model  was used for producing one-step ahead, dynamic, and future forecasts.


<img src='/images/ml4_future_forecasts.png'>


The future forecasts indicate that the CO2 time series is expected to continue increasing.