## cereals_pulses_production_forecasting
This project focuses on forecasting cereals and pulses production in Maharashtra using advanced time series forecasting techniques. Accurate forecasting of agricultural production is essential for policymakers, farmers and agricultural planners to ensure food security, efficient resource allocation and economic stability.

This study applies and compares three forecasting models:

ARIMA (AutoRegressive Integrated Moving Average)

Holt–Winters Exponential Smoothing

LSTM (Long Short-Term Memory Neural Network)

The objective is to identify the most accurate model for forecasting agricultural production.
Dataset Information

Source: Directorate of Economics and Statistics, Ministry of Agriculture, Government of India

Location: Maharashtra, India

Time period: 1997 – 2023

Crop categories:

Cereals (Jowar, Bajra, Rice, Maize, Wheat)

Pulses (Tur, Gram, Moong, Urad, etc.)
Variables include:

Year

Crop production (tonnes)

Area

Yield

Crop type
Methodology
1. Data Preprocessing

Data cleaning

Handling missing values

Outlier detection

Time series formatting

2. Stationarity Test

Augmented Dickey–Fuller (ADF) Test used

Result: Series was stationary (p-value < 0.05)

3. Models Applied
ARIMA Model

Captures trend and autocorrelation

Best performing model

Holt–Winters Model

Captures trend and smoothing patterns

Moderate performance

LSTM Model

Deep learning model

Captures nonlinear patterns

Requires large dataset
