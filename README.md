# Stock Price Prediction

A machine learning project that predicts stock price movements using technical indicators and a Random Forest Classifier.

## Features

- Downloads historical stock data using `yfinance`
- Calculates technical indicators: RSI, ATR, MACD, Bollinger Bands, EMA crossover signals
- Trains a Random Forest model to predict 5-day price trends
- Visualizes results with interactive candlestick charts using `mplfinance`
- Provides trading tips (Buy/Hold/Sell) based on model predictions

## Installation

```bash
pip install -r requirements.txt
