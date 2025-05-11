# Code Breakdown for AAPL-LSTM-Stock-Predictor

## Overview
This project aims to predict AAPL stock prices using an LSTM model built with TensorFlow and Keras.

## Libraries and Dependencies
- `yfinance`: To download historical stock data.
- `numpy`: For numerical operations and handling arrays.
- `pandas`: To manage and preprocess data.
- `matplotlib`: For visualizing the stock price data.
- `sklearn`: For MinMax scaling and performance metrics.
- `tensorflow`: For building and training the LSTM model.

## Code Walkthrough

### 1. Data Download and Preprocessing
- We use `yfinance` to fetch AAPL stock data from 2022 to 2024.
- Only the 'Close' price is used in the analysis.
- The data is scaled between 0 and 1 using `MinMaxScaler` for better LSTM performance.

### 2. Sequence Creation
- We create sequences of 60 days' worth of data to predict the next day's closing price.
- The function `create_sequences()` generates sequences that are used as input (`X`) and target (`y`) for the model.

### 3. LSTM Model Definition
- An LSTM model is built with two LSTM layers and a Dense output layer.
- The model is trained on the training data and validated on the test data.

### 4. Prediction and Evaluation
- The model predicts the stock prices, which are then scaled back to their original values.
- The Root Mean Squared Error (RMSE) metric is calculated to assess the model's accuracy.

## Conclusion
This model shows the predicted stock prices for Apple, compared to the actual values. Further improvements could include hyperparameter tuning and adding more features like volume or other technical indicators.
