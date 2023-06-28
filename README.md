# Time-series-Analysis-using-ARIMA
It is a case study to forecast  energy consumption there are four features in the dataset
demand,temp,precip and timestamp
so my first step was to make timestap column a index and parse it 
Then i plot ACf and PAcf plots to identify p,d,q values for the ARIMA model
p=AR order
d-integration order
q=Moving Average order
Then i used pmdarima to get the values of p,d,qthen applied ARIMA model to forecast.
