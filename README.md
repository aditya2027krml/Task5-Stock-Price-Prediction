Task-5

Sock Price Prediction;

Problem Statement:
Create a model to predict stock prices based on historical market data.

This project leverages time-series analysis to forecast stock prices, deploying a Streamlit web application via FastAPI. The application fetches up to 10 years of historical stock data from Yahoo Finance (yfinance) for a user-specified ticker symbol (e.g., GOOG). It then calculates and visualizes 50-day, 100-day, and 200-day moving averages (MA50, MA100, MA200) to identify trends and potential buy/sell signals. A Long Short-Term Memory (LSTM) model, trained on 80% of the historical data, predicts future stock prices. Finally, the app presents a comparative visualization of original vs. predicted prices, enabling users to assess model accuracy and inform investment decisions. The LSTM model takes 100 days of past data, the model predict the next day's price.


