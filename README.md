## 🧠 Project Title
**Predicting Future Stock Prices using LSTM Neural Networks and Technical Indicators**

---

## 📝 Problem Statement

The stock market is highly volatile and influenced by various technical factors. Investors need a reliable way to forecast future stock prices for better decision-making. This project aims to develop a deep learning model using LSTM (Long Short-Term Memory) networks to predict **Open** and **Close** prices of top 50 Indian stocks based on historical technical indicators, without relying on fundamental data.

---

## 🧪 Technology and Algorithms Used

- **Language:** Python  
- **Frameworks & Libraries:** 
  - `TensorFlow`, `Keras` – for building and training the LSTM model  
  - `NumPy`, `Pandas`, `Matplotlib` – for data processing and visualization  
  - `yfinance` – to fetch historical stock market data  
  - `scikit-learn` – for scaling and evaluation  
- **Algorithm:** 
  - **LSTM (Long Short-Term Memory)** – a variant of RNN designed to learn long-term dependencies in sequential data. Suitable for time-series prediction tasks such as financial forecasting.

---

## 📊 Dataset Description

- **Source:** [Yahoo Finance](https://finance.yahoo.com/) via `yfinance`  
- **Time Range:** January 1, 2019 – 2025  
- **Stocks:** 50 major Indian NSE-listed stocks (e.g., `RELIANCE.NS`, `TCS.NS`, `INFY.NS`, etc.)

### Features Used:

| Category          | Indicators |
|------------------|------------|
| **Raw Prices**    | Open, High, Low, Close, Volume |
| **Technical Indicators** | Daily Returns, RSI, MACD, SMA-10, SMA-50, EMA-10, Bollinger Bands, ATR, OBV, Historical Volatility |

- Data is cleaned, scaled, and transformed into **180-day sequences** used to predict the next day’s **Open and Close** prices.

---


