# Stock Price Prediction Time Series using ARIMA

## Overview
This project focuses on predicting stock prices using the Autoregressive Integrated Moving Average (ARIMA) model. Time series analysis and ARIMA modeling are employed to forecast future stock prices based on historical data.

## Table of Contents
1. Introduction
2. Data Cleaning
3. Data Exploration
4. Stationarity Checks
5. Decomposition
6. Differencing
7. ACF and PACF Analysis
8. ARIMA Model
9. Model Evaluation
10. Alternative ARIMA Model with pmdarima

## Introduction
The Stock Price Prediction Time Series project employs the ARIMA model to predict future stock prices based on historical data. The objective is to provide accurate forecasting, aiding investors and analysts in making informed decisions.

## Data Cleaning
Clean the dataset by removing missing values and converting the 'Date' column to datetime format.

## Data Exploration
Explore the historical stock prices through visualization to understand patterns and trends.

## Stationarity Checks
Check stationarity using rolling statistics and the Augmented Dickey-Fuller (ADF) test.

## Decomposition
Decompose the time series into trend, seasonality, and residuals for a better understanding of the underlying patterns.

## Differencing
Apply differencing to make the time series stationary.

## ACF and PACF Analysis
Analyze AutoCorrelation Function (ACF) and Partial AutoCorrelation Function (PACF) to determine the order of AutoRegressive (AR) and Moving Average (MA) components.

## ARIMA Model
Build the ARIMA model using the determined order and fit it to the differenced time series.

## Model Evaluation
Evaluate the performance of the ARIMA model and visualize the predictions against the actual stock prices.

## Alternative ARIMA Model with pmdarima
Explore an alternative ARIMA model using the pmdarima library for automated order selection.

## Support
For any issues or inquiries, please contact hadiaj2002@gmail.com.
