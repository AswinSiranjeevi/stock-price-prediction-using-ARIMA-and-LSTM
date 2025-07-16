# stock-price-prediction-using-ARIMA-and-LSTM
This project leverages the power of statistical modeling (ARIMA) and deep learning (LSTM neural networks) to forecast stock prices. By comparing these two approaches, we gain insight into the performance of traditional time-series forecasting versus modern sequence models.

# 🚀Project Overview
Predicting the stock market is notoriously difficult—but not impossible. This project attempts to model stock price behavior using:

ARIMA (AutoRegressive Integrated Moving Average) for statistical time-series forecasting.

LSTM (Long Short-Term Memory) networks for deep learning-based sequence prediction.

Both models are applied to Apple Inc. (AAPL) stock data to evaluate forecasting capabilities and accuracy.

# 📉 Data Source

Stock data is fetched directly using yfinance, focusing on AAPL historical daily prices from Yahoo Finance.

# 🔍 Features
✅ Data preprocessing: Handling missing values, scaling, and splitting into train/test.

📈 ARIMA model: Auto ARIMA order selection and forecasting with confidence intervals.

🧠 LSTM model: Windowed data preparation, model architecture with memory cells, and multi-epoch training.

📊 Visualization: Actual vs predicted price plots for both models.

📉 Error Metrics: RMSE comparison between ARIMA and LSTM predictions.

