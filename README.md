# Time Series Analysis and Forecasting 

## What is time series? 
Time series is a series of dependent data points that are indexed in time order, usually taken at successive and equally spaced points in time.

## Testing stationarity 
Stationarity is an important concept in time series analysis. Most time series models such as ARIMA assume that each data point is independent of one another.
In other words, before we can fit a time series model to the data and use the model to make predictions, we need to first ensure that the time series is stationary.

A time series is considered stationary if it satisifies the following 3 conditions:
1. The expected value (mean) is constant over time
2. The volatility (variance) of the time series is constant around its mean over time
3. The covariance of the time series depends only on the time lag

Visually speaking, there are two components to a time series that determine whether or not it is stationary: trend and seasonality.

There are two methods for testing stationarity:
1. Phillips-Perron Unit Root Test
2. Plotting the sample ACF

## Removing trend
There are a few ways to remove trends. The two simplest methods are:
1. Differencing
2. Least squares trend removal 

Differencing means taking the difference between the data point and a previous data point of a given lag. The least-square trends removal, on the other hand,
involves fitting a linear model to the time series and subtracting the fitted values from the data points.

## Removing seasonality 
Three methods to eliminate seasonality from a time series include:
1. Seasonal differencing
2. Seasonal means
3. Method of moving averages 

Seasonal differencing means subtracting each data point by a previous data point of a fixed lag. Seasonal means involves subtracting each data point by their respective group averages,
for instance in this particular scenario, the monthly average. Last but not least, the method of moving averages involves calculating the trend of a time series by taking the moving average over the entire time series.

## Fitting an ARIMA model 
The ARIMA model is one of the most commonly used time series models. It is made up of three hyperparameters:
1. Autoregression (AR)
2. Differencing (I)
3. Moving average (MA)

## Testing the fit of a model
Three ways to testing the goodness of fit of a time series model include:
1. Graph of residuals 
2. Ljung-Box test 
3. Akaike Information Criterion (AIC) 

Graph of residuals, as the name suggests, plots the residuals of the time series data that are not accounted for by the model. 
The Ljung-Box test is a statistical test that measures whether or not a group of autocorrelations of a time series are different than zero.
Last but not least, the AIC is a measure of the trade-off between the goodness of fit of a model and the number of parameters used in the model.

## Medium article 
Link to full write-up on Towards Data Science [here](https://towardsdatascience.com/beginners-introduction-to-time-series-analysis-and-forecasting-c2c2918603d9).

## Follow me 
- [Facebook](https://www.facebook.com/chongjason914)
- [Instagram](https://www.instagram.com/chongjason914)
- [Twitter](https://www.twitter.com/chongjason914)
- [LinkedIn](https://www.linkedin.com/in/chongjason914)
- [YouTube](https://www.youtube.com/jasonchong914)
- [Medium](https://www.medium.com/@chongjason)
