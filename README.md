# Passenger-Traffic-Forecasting-for-Airlines

# Time Series Forecasting with Holt-Winters and ARIMA Models

## Introduction
This repository contains a time series forecasting project using two popular forecasting techniques: Holt-Winters Exponential Smoothing and Auto Regressive Integrated Moving Average (ARIMA). The project focuses on forecasting monthly air passenger data by applying additive and multiplicative Holt-Winters methods, as well as building ARIMA models on transformed data. The analysis involves identifying trends, seasonality, and converting non-stationary data into stationary time series to improve model performance.

## Project Structure
- Holt-Winters Exponential Smoothing**
  - Implements both additive and multiplicative methods for forecasting.
  - Evaluates the model using RMSE and MAPE metrics.
  - Visualizes the performance and analysis of forecast results.

-  Auto Regressive Models (AR) and ARIMA**
  - Analyzes stationarity of the time series using ADF and KPSS tests.
  - Converts non-stationary data to stationary using Box-Cox transformation and differencing.
  - Builds and evaluates ARIMA models on the transformed data.
  - Visualizes ACF and PACF to identify appropriate ARIMA parameters.

## Key Libraries Used
- `numpy`, `pandas`: For data manipulation.
- `matplotlib`: For visualizations.
- `statsmodels`: For time series models, stationarity tests, and ACF/PACF plots.
- `scipy`: For Box-Cox transformation.

## Holt-Winters Exponential Smoothing
1. **Additive Method:**
   - Captures level, trend, and seasonality.
   - Forecasts last 24 months using additive trend and seasonality.
   - Visualizes forecast results and evaluates performance using RMSE and MAPE.

2. **Multiplicative Method:**
   - Similar to the additive method but uses a multiplicative approach for seasonality.
   - Compares the results of additive and multiplicative methods.

## Auto Regressive Models (AR) and ARIMA
1. **Stationarity Analysis:**
   - Uses Augmented Dickey-Fuller (ADF) and KPSS tests to check stationarity.
   - Converts the non-stationary time series to stationary using Box-Cox transformation and differencing.

2. **Autocorrelation Analysis:**
   - Visualizes ACF and PACF to identify the lag periods for the ARIMA model.

3. **ARIMA Model:**
   - Builds a simple Auto Regressive (AR) model with differenced data.
   - Further explores ARIMA models for better forecasting results.

## Conclusion
This project demonstrates the application of Holt-Winters and ARIMA methods for forecasting time series data. The analysis shows how transforming non-stationary data and selecting appropriate model parameters can lead to more accurate forecasts.

