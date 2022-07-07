# Bitcoin-Price-Prediction
Bitcoin Price Prediction using ARIMA Model and LSTM network

This project is about building a model that is efficient in predicting Bitcoin Prices
The dataset for this project will be taken from the yahoo finance API
The dataset is Bitcoin vs USD (BTC-USD) prices

In this project , the close price of Bitcoin is the category that is being focused on
The model is coded in Python and the tool used is Google Colab
The prediction has been done using 2 models
The first model is the ARIMA time series model where tests were conducted to check
if data is stationary
The data in this case being non stationary , the data has been decomposed and ready
to be passed to the Auto Arima model
Also an ARIMA model was build with one case where the values of p,d,q were
assumed
