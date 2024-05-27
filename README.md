# stock-prediction
Stock Prediction App

This is a simple Streamlit app that allows users to forecast stock prices using Facebook's Prophet library and Yahoo Finance data.
To use the app, you can run the code directly in a Streamlit-enabled environment. First, you need to install the necessary libraries using pip:

pip install streamlit fbprophet yfinance plotly

Then, you can clone this repository and run the stock_forecast_app.py file in your Streamlit environment:

streamlit run stock_forecast_app.py

This will launch the app in your web browser. You can then select the stock dataset and the number of years you want to forecast. The app will display the raw data, the forecast data, and the forecast plot.
Note: The data loading process can take a while if you are running the app for the first time. This is because the data is being cached. In subsequent runs, the data will be loaded much faster.

#How it works

1.The app allows the user to select a stock dataset from the available options.
2.The user can also choose the number of years they want to forecast into the future.
3.The selected stock data is loaded using the yfinance library.
4.The loaded data is plotted using Plotly.
5.A Prophet forecast model is created and fitted to the stock data.
6.A future dataframe is created with the specified number of periods for forecasting.
7.The forecast is made using the Prophet model and the future dataframe.
8.The forecast data is displayed along with the forecast plot.

#Data source

The stock data used in this app is fetched from Yahoo Finance using the yfinance library.
