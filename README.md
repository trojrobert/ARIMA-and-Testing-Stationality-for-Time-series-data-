Test Stationality and Arima on Time series data 
**we use Air Passenger dataset and daily Daily minimum temperatures in Melbourne dataset**

## Stationarity

A common assumption in many time series techniques is that the data are stationary.
A stationary process has the property that the mean, variance and autocorrelation structure do not change over time. Stationarity can be defined in precise mathematical terms, but for our purpose we mean a flat looking series, without trend, constant variance over time, a constant autocorrelation structure over time and no periodic fluctuation

## Procedure

1. Read the dataset as a series 
2. Display table and visualize the Air two dataset
3. check if the mean and the moving variance varies with time 
4. Using Summary Statistics to test for stationary 
5. Make the non-stationary dataset stationary
6. Using EWMA to make the time series stationary
7. Using First-Order Difference to make the time series stationary

## Arima 
ARIMA is an acronym that stands for AutoRegressive Integrated Moving Average. It is a class of model that captures a suite of different standard temporal structures in time series data. The Model can be used 

This acronym is descriptive, capturing the key aspects of the model itself. Briefly, they are:

AR: Autoregression. A model that uses the dependent relationship between an observation and some number of lagged observations.
I: Integrated. The use of differencing of raw observations (e.g. subtracting an observation from an observation at the previous time step) in order to make the time series stationary.
MA: Moving Average. A model that uses the dependency between an observation and a residual error from a moving average model applied to lagged observations.

### Procedure

+ import the data 
+ visualize the data set on a plot 
+ Use manual process to predict combination of parameters to fit seasonal ARIMA model 
+ Rolling Forecast ARIMA Model
+ Use "grid search" to iteratively explore different combinations of parameters
+ Using dynamic forecasts
