---
title: "CO₂ Emissions Forecasting"
excerpt: "Developed and evaluated time series forecasting models; one-step ahead model achieved a 95% lower Mean Squared Error (MSE = 0.09) compared to dynamic forecasts (MSE = 2.01).<br/>"

collection: machinelearning
---
The analysis focuses on CO₂ atmospheric concentrations dataset. It covers data preparation and exploration using visualization and STL decomposition, checking stationarity by applying the Dickey-Fuller test and computing and plotting the ACF and PACF values. I also built a seasonal ARIMA model to produce one-step ahead, dynamic and future forecasts for CO₂ emissions forecasting.
<br/>

[GitHub](https://github.com/ciDSproj/timeseries_forecast)

---


Using grid search were identified the best parameters for building a seasonal ARIMA model. The model  was used for producing one-step ahead, dynamic, and future forecasts.


<img src='/images/ml4_future_forecasts.png'>


The future forecasts indicate that the CO2 time series is expected to continue increasing.