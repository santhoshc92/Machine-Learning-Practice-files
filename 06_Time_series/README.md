**AirPassengers Time Series Forecasting**

This project performs time series analysis and forecasting on the classic AirPassengers dataset, which contains monthly totals of international airline passengers from 1949 to 1960.
The goal is to forecast future passenger numbers using statistical time series models.

**Data set Description:**

| Feature        | Description                                      |
| -------------- | ------------------------------------------------ |
| **Month**      | Monthly time index (1949–1960)                   |
| **Passengers** | Total number of international airline passengers |

**Project Objective**

Explore and visualize the time series

Apply transformations such as log scaling and rolling statistics

Test for stationarity using the Augmented Dickey-Fuller (ADF) test

Perform seasonal decomposition

Build forecasting models including:

	ARIMA

	Auto-ARIMA

	SARIMAX
Generate and evaluate future forecasts
**Stationarity Test**

ADF (Augmented Dickey-Fuller) Test - Used adfuller() to check whether the series is stationary

**Seasonal Decomposition**

Decomposed the series into:

Trend

Seasonality

Residuals

**Models Performed**
ARIMA
SARIMAX

**Technologies Used**

Python

Pandas

NumPy

Matplotlib / Seaborn

Statsmodels (ARIMA, SARIMAX, seasonal decomposition, ADF test)

pmdarima (Auto-ARIMA)

Jupyter Notebook
