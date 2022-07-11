# Exxon-Stock-Forecasting-VAR
Forecasting Exxon's stock price using VAR (vector autoregression) using fundamental and market data as regressors

Forecasting Exxon's (XOM) Stock Price with VAR (Vector Autoregression)
"All models are wrong but some are useful" - George E. P. Box


Here we present a novel way to predict the price of Exxon's stock (XOM) in a short term horizon (days or weeks).

VAR (Vetor Autoregression) is a model that comes in very useful when trying to predict time series data while also wanting to learn something from adjacent time series.

The way it works, is that it gathers information from its own time series attributes (in this case our stock), while learning from the time series attributes of other time series data, in this case, data we hypothesize influences the stock price.

We will define such variables/time series as follows:
- XOM Price: The Exxon stock price
- S&P 500: The S&P 500 stock market index
- WTI Price: The price of the West Texas Intermediate (US) crude oil barrel
- Brent Price: The price of the Brent (EU) crude oil barrel
- Production: US crude oil production
- Consumption: US consumption of oil products
- Inventory (Crude): US crude oil inventory
- Input to Refineries: US refiner crude oil consumption
- Inventory (Gas): US inventory of gasoline
