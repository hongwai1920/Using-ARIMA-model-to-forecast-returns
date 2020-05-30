# Using ARIMA model to forecast returns
This repository contains a detailed theoretical and practical introduction to time series analysis models such as AutoRegressive (AR), Moving Average (MA), AutoRegressive Moving Average (ARMA) and AutoRegressive Integrated Moving Average (ARIMA). 

We also introduced and implemented several stationarity tests such as Augmented Dickey-Fuller (ADF) test and KPSS.  
We use Python's library statsmodels to implement all models above and use the ARIMA model to forecast future stock prices.

All datasets in csv are obtained from Yahoo Finance.

## 0. Introduction.ipynb
This notebook gives a flavour of how to use ARIMA to predict stock prices. 
The following is a plot of using ARIMA(5,2,0) to predict Apple'stock price with mean square error 1.640.
<p align="center"> <img  src="https://github.com/hongwai1920/Using-ARIMA-model-to-forecast-returns/blob/master/Images/AAPL%20ARIMA.png" width="500" height="400"></p>


## 1. Simulations for Time Series Models.ipynb
This notebook introduces time series.
The following four time series are the open, high, low and close prices of Apple's stock.
<p align="center"> <img  src="https://github.com/hongwai1920/Using-ARIMA-model-to-forecast-returns/blob/master/Images/AAPL%20OHLC.png" ></p>
