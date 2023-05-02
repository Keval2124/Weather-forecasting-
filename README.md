# Weather forecasting with prophet and neural prophet

Weather forecasting is the process of predicting weather conditions for a given location and time. Prophet and Neural Prophet are two open-source time-series forecasting libraries developed by Facebook that can be used for weather forecasting.

Prophet is a forecasting library that uses an additive model to fit trends, seasonality, and holiday effects. It is designed to handle time series with multiple seasonality, and it can also incorporate external regressors. To use Prophet for weather forecasting, historical weather data can be used to train the model, and the model can be used to predict future weather conditions. 

Neural Prophet is an extension of Prophet that uses neural networks to model time series data. It is designed to handle large datasets with multiple time scales and non-linear trends. Neural Prophet can be used for weather forecasting by using historical weather data to train the neural network and predicting future weather conditions. The resulting forecasts can be used to provide more accurate and detailed weather predictions than traditional forecasting methods.

Both Prophet and Neural Prophet can be used to forecast various weather variables such as temperature, humidity, precipitation, and wind speed. They can also be used to handle missing data, outliers, and anomalies in the weather data. Overall, these libraries provide a powerful and flexible toolset for weather forecasting, enabling organizations to make data-driven decisions based on accurate and reliable weather predictions.
Let’s understand terminology :
In Prophet:
- yhat: This is the predicted value of the target variable at a given time point. Prophet uses a Bayesian regression model to estimate this value.
- yhat_upper: This is the upper bound of the uncertainty interval for the predicted value. Prophet calculates this interval by taking the 95th percentile of the posterior distribution of the predicted value.
- yhat_lower: This is the lower bound of the uncertainty interval for the predicted value. Prophet calculates this interval by taking the 5th percentile of the posterior distribution of the predicted value.

In NeuralProphet:
- yhat1: This is also the predicted value of the target variable at a given time point. NeuralProphet uses a feedforward neural network to make predictions.
