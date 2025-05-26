# Apple Stock Price Forecasting with Sentiment Analysis using LSTM

This project forecasts Apple stock prices by combining historical closing prices with daily sentiment scores extracted from news headlines using a Hugging Face sentiment analysis model. The forecasting is done using a Long Short-Term Memory (LSTM) neural network.

---

## Project Overview

- **Data:**  
  - Apple stock closing prices (daily, excluding weekends) from 2023-05-24 to 2025-05-23  
  - Daily sentiment scores derived from Apple-related news articles

- **Goal:**  
  To predict the next day’s Apple stock closing price using both historical prices and sentiment data.

- **Model:**  
  LSTM model trained on sequences of past 60 days of price and sentiment data.
