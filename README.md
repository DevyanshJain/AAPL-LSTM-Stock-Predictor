# 📈 AAPL LSTM Stock Predictor

This project uses a Long Short-Term Memory (LSTM) neural network to predict the closing prices of Apple Inc. (AAPL) stock using historical data.

## 🧠 Model Overview
- **Data Source**: Yahoo Finance (via `yfinance`)
- **Model Type**: Sequential LSTM Neural Network
- **Libraries Used**: TensorFlow, Keras, NumPy, Pandas, scikit-learn, Matplotlib
- **Performance Metric**: RMSE = 3.15

## 📊 Project Features
- Fetches Apple stock data from 2022 to 2024
- Normalizes the data using MinMaxScaler
- Uses sliding window technique to create sequences
- Trains a two-layer LSTM model
- Predicts and visualizes actual vs predicted prices

## 📁 Files
- `AAPL_Stock_Price_Prediction_LSTM.ipynb`: Full implementation notebook

## 📷 Sample Output
![Prediction Plot](https://github.com/DevyanshJain/AAPL-LSTM-Stock-Predictor/blob/main/prediction_plot.png?raw=true)


## 🚀 How to Run
1. Clone this repo:
    ```bash
    git clone https://github.com/YourUsername/AAPL-LSTM-Stock-Predictor.git
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the notebook using Jupyter or VS Code.

## 🧠 Future Improvements
- Add more features (volume, technical indicators)
- Hyperparameter tuning
- Try other architectures like GRU or Transformer

---

## 🧑‍💻 Author
**Devyansh Jain**

---

