
# 🧠 Crypto Forecast Bot

[Download here](https://github.com/rondaredmind-2000/Crypto-Forecast-Bot/releases)

**Crypto Forecast Bot** is an AI-powered chatbot that uses 10 years of historical data from Yahoo Finance to predict future prices for popular cryptocurrencies like **Bitcoin (BTC)** and **Ethereum (ETH)**. It leverages machine learning with Facebook Prophet to forecast price trends and helps users make informed decisions.

---

## 🚀 Features
- 📈 Pulls real-time data from **Yahoo Finance**.
- 🔁 Allows users to **refresh market data** before generating predictions.
- 📅 Generates **30-day price forecasts** for supported coins using time-series analysis.
- 🧠 Understands **natural language** queries like:
  - `"Refresh BTC"`
  - `"Predict ETH for next 14 days"`
  - `"Show forecast for BTC"`
- 💬 Simple and friendly **chatbot UI** powered by **Gradio**.

---

## 💻 Technologies Used
- `Python`
- `yfinance` – for retrieving historical price data
- `Prophet` – for forecasting crypto trends
- `Gradio` – to create a conversational chatbot interface
- `pandas`, `matplotlib` – for data processing and plotting

---

## 📌 How to Use
1. Launch the notebook in **Google Colab** or locally in Jupyter.
2. Run all code cells to initialize the bot and its data.
3. Interact via the chatbot interface:
   - Type `"Refresh BTC"` to pull the latest Bitcoin data.
   - Type `"Predict ETH for next 30 days"` to get a forecast.
   - Type `"Plot BTC"` to view a graph of predicted prices.

---

## 📝 Supported Commands

| User Input | Description |
|------------|-------------|
| `refresh BTC` | Refreshes latest data for Bitcoin |
| `refresh ETH` | Refreshes latest data for Ethereum |
| `predict BTC for next 7 days` | Predicts Bitcoin prices for the next 7 days |
| `predict ETH for next 30 days` | Predicts Ethereum prices for the next 30 days |
| `help` | Shows available commands |
| `exit` | Ends the chat session |

---

## ⚠️ Disclaimer
This bot provides **educational forecasts** based on historical data and statistical modeling. It is **not financial advice**. Cryptocurrency markets are volatile — always do your own research before investing.
