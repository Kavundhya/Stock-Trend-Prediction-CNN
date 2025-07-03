# Stock-Trend-Prediction-CNN
CNN-based stock trend prediction model using technical indicators and slope-detection labeling. Implements a research paper approach for short-term price forecasting with backtesting capabilities.

# Short-Term Price Trend Prediction Model
Implementation of a CNN-based trend prediction system using slope-detection labeling, as described in [Short-Term Stock Price-Trend Prediction Using Meta-Learning](#) (Chang et al.).

## Features
- **Data**: Fetches SPY OHLCV data via `yfinance`.
- **Indicators**: EMA20, MACD, Momentum, RSI, ATR.
- **Labeling**: 4-class slope-detection (Rise Plus, Rise, Fall, Fall Plus).
- **Model**: 1D CNN trained on 22-day sequences.
- **Backtest**: Strategy buys on "Rise" signals (65% confidence).
