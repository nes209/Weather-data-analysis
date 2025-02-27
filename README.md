# Weather Data Analysis and Forecasting Using ARIMA and SARIMA Models

## Project Description:
This project aims to analyze and forecast temporal weather data using ARIMA and SARIMA models. The project includes data processing, stability analysis, correlation and seasonality analysis, ARIMA/SARIMA modeling, residual analysis, and future forecasting.

• Data was uploaded from CSV file from kaggle " https://www.kaggle.com/datasets/prasad22/weather-data "

• Stability analysis: Using ADF test to check the stability of time series.

• Correlation and seasonality analysis: Using ACF and PACF plots to determine p and q values ​​in ARIMA model, and using seasonal decomposition analysis to determine P, D, and Q values ​​in SARIMA model.

• ARIMA/SARIMA modeling: Using grid search to select the best p, d, q, P, D, and Q values ​​that achieve the lowest RMSE, and training SARIMA model using the best values.

• Residual analysis: Analyzing the model residuals using histograms and Ljung-Box test to check their randomness and independence.

• Forecasting: Using SARIMA model to forecast future values ​​of time series, and plotting forecasts with confidence intervals.

## Requirements:
* Python 3.6+

* NumPy

* Pandas

* Matplotlib

* Seaborn

* Statsmodels

* Scikit-learn

## Results:

* SARIMA models were found to perform well in forecasting weather data.

* The stationarity of time series and randomness of residuals were checked.

* The forecasts were plotted with confidence intervals to illustrate the accuracy of the forecasts.

## Conclusions:

* SARIMA models can be used to forecast weather data with acceptable accuracy.

* Care should be taken to process the data and analyze stability, correlation, and seasonality before training the models.

* The residuals of the models should be verified to ensure the validity of the results.

## Recommendations:

* The accuracy of the forecasts can be improved by using more complex models or adding external variables.

* Other machine learning techniques such as LSTM or GRU can be used to forecast weather data.

* Cross-validation can be used to validate the results
