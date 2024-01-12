# Stock Market Predictor

This is a simple stock market prediction project using Long Short-Term Memory (LSTM) neural networks. The project uses historical stock data from Yahoo Finance, implemented using the `yfinance` library, and the LSTM model is built using the `keras` library.

## Project Overview

The project consists of two main parts:

1. **Training the LSTM Model:**
   - Downloads historical stock data for a given stock symbol.
   - Implements a simple Moving Average (MA) analysis.
   - Splits the data into training and testing sets.
   - Scales the data using Min-Max scaling.
   - Builds and trains an LSTM model for stock price prediction.
   - Saves the trained model for future use.

2. **Streamlit Web App:**
   - Uses the trained model to make predictions.
   - Provides an interactive web interface using Streamlit.
   - Displays stock data, Moving Averages, and predicted vs original prices.

## Dependencies

- `numpy`
- `pandas`
- `matplotlib`
- `yfinance`
- `scikit-learn`
- `keras`
- `streamlit`

## Demo Img and Link
<img width="889" alt="image" src="https://github.com/Deepakv1210/Stock_Crypto_Market_Prediction/assets/154148155/619ceef0-e093-4b70-b74f-c0678c62f934">
https://stockcryptomarketprediction.streamlit.app/
