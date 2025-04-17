# UK Stock Market Forecasting and Analysis

## Overview
This project analyzes and forecasts the UK stock market using multiple time series techniques. The notebook processes historical data, performs data cleaning and scaling, and uses statistical (ARIMA, SARIMAX) as well as deep learning (LSTM) and machine learning models (Prophet) to predict future prices. Additionally, volatility forecasting methods like GARCH and ARCH are applied.

## Requirements
- Python 3.12
- Packages: pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels, tensorflow, prophet, arch, and others as required.

## Project Structure
- **Data Loading & Preprocessing:** Read and clean the dataset ('UK_Stock_Market_2024_Onwards.csv'), handle NaNs, and perform scaling.
- **Exploratory Data Analysis:** Generate plots (line plots, ACF, PACF) to visualize historical close price trends.
- **Forecasting Models:**
  - **ARIMA/SARIMA:** Fit ARIMA models to generate forecasts.
  - **LSTM:** Build and evaluate an LSTM model on scaled data.
  - **Prophet:** Perform forecasting with the Facebook Prophet model.
  - **GARCH/ARCH:** Forecast volatility using ARCH and GARCH models.
- **Evaluation:** Calculate evaluation metrics such as MAE, MSE, RMSE, R-squared, and visualize residuals.