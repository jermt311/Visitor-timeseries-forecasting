# Timeseries Forecasting

## Background

While often negleted, time series forecasting is a very important area of machine learning. There are many prediction problems thjat involve a time component. It is important to be aware of this time component when making predictions as it does make time series more difficult to handle by using simple prediction methods. 

## Project Description

In this project, I will use “Visitors.csv” data to forecast 24 months of monthly number of
visitors to a country following the last period in the dataset. The aim of the project is to develop univariate forecasting models using only the historical number of visitors.

In this project, I decided to explore the use of a few different timeseries forecasting methods and compare the different model performances. 
- SARIMA (Seasonal Autoregressive Integrated Moving Average)
- Holt Winters (Multiplicative)
- Simple Random Walk
- Simple Exponential Smoothing
- Holt-Winters Multiplicative Damping
- Holt Winters (Additive)


## Forecasting

Out of the five (5) selected timeseries models, I decided to only use the Holt Winters model and the SARIMA model to conduct a tiemseries forecast for 24 months (2 years).
