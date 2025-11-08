# forexUSD2IDR

This project explores the application of Data Analytics and Machine Learning to predict currency exchange rates between USD and IDR.

The study compares three time-series forecasting models:
-ARIMA
-Facebook Prophet (fbprophet)
-Long Short-Term Memory (LSTM)

All of these models using both univariate and multivariate datasets derived from historical financial data and economic indicators (except for ARIMA which only handles the univariate dataset).

## Data Description

1. Historical exchange rates between USD (United States Dollar) and IDR (Indonesian Rupiah) via Yahoo Finance (yfinance)
2. Macroeconomic Data (Interest Rate, Inflation Rate, Trade Balance, Current Account, Foreign Exhange Reserve)

## Tools and Library

- Pandas
- Numpy
- Matplotlib
- Seaborn
- statsmodel (for ARIMA)
- scikit-learn
- tensorflow
- keras
- fbprophet

## Model Architecture

1. ARIMA (AutoRegressive Integrated Moving Average)
  - Handles univariate time-series data
  - Suitable for seasonal patterns
  - Limited in capturing multiple economic indicators simultaneously

2. Facebook Prophet (fbprophet)
  - Capture both univariate and multivariate forecasting
  - Easy to tune and visualize trends and seasonality
  - Highly sensitive to hyperparameters and missing data

4. LSTM (Long Short-Term Memory)
  - Handles sequential and non-linear data
  - Retains long-term dependencies
  - Supports both univariate and multivariate input
  - Requires data scaling and inverse transformations for interpretation

## Model Evaluation Metrics

1. R2 (R-Squared)
2. MAE (Mean Absolute Error)
3. MSE (Mean Squared Error)
4. RMSE (Root Mean Squared Error)
