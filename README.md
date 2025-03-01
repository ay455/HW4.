# HW4.
This project looks at average monthly surface temperature data and uses different time series models to predict future trends. The data includes temperature readings for both AM and PM, and we start by exploring patterns, trends, and seasonality using graphs and decomposition techniques. To make predictions, we test several forecasting methods, including the naive model as a simple baseline, the seasonal naive model to account for repeating patterns, the Holt-Winters model for trends and seasonality, the ETS model for flexible smoothing, and STL-based forecasting, which breaks the data into components before predicting. We compare these models using RMSE and MAE, which measure how accurate the predictions are, and pick the one with the lowest RMSE as the best option. After evaluating the results, the best model for predicting AM temperatures is, while the best model for PM temperatures, giving us the most reliable forecasts for future temperatures.
