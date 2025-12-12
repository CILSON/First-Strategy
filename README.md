# 📘 50/200 SMA Crossover Trading Strategy


# Overview

This repository contains a Jupyter notebook that implements and backtests a classic 50/200 Simple Moving Average (SMA) Crossover Strategy.
The notebook covers data loading, preprocessing, trading signal generation, backtesting, and performance visualization.
This project is intended as a simple and clear example for learning the basics of strategy development in Python -- all inside Google Colab

# 🧠 Strategy Logic

The strategy uses two moving averages:

SMA 50 (short-term trend)

SMA 200 (long-term trend)

Rules:

Buy when SMA 50 crosses above SMA 200 (Golden Cross)

Sell when SMA 50 crosses below SMA 200 (Death Cross)

This is one of the most widely known trend-following strategies.

# 📂 Notebook Contents

Importing and cleaning price data

Calculating SMA indicators

Generating buy signals

Running a simple backtest

Plotting signals and equity curve

Basic performance summary

# How to Run

Click the link below to open the notebook directly in Google Colab:

https://colab.research.google.com/github/CILSON/First-Strategy/ALGO1.ipynb

# 🛠 Dependencies

Common libraries used:

pandas

numpy

yfinance (or other data source)

# ⚠️ Disclaimer

This project is for educational purposes only and not financial advice.

# 📄 License (MIT)

This project is licensed under the MIT License — you are free to use, modify, and distribute the code with proper attribution.
