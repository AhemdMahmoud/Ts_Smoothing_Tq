### Time Series Forecasting using `Smoothing Methods`
This notebook explores time series forecasting through various smoothing techniques. Specifically, it covers the following methods:

`Single Exponential Smoothing (SES)`

SES is a time series forecasting method for univariate data without trend or seasonal components. It applies exponential decay to past observations, assigning exponentially decreasing weights over time.

`Double Exponential Smoothing (DES)`

DES, also known as Holt's linear trend model, extends SES to capture trends in the data. It includes two components: level and trend, making it suitable for data with linear trends but without seasonality.

`Triple Exponential Smoothing (TES) / Holt-Winters
TES, also known as the Holt-Winters method` , further extends DES by incorporating seasonality. It includes three components: level, trend, and seasonal, making it ideal for time series data with both trend and seasonal patterns.
