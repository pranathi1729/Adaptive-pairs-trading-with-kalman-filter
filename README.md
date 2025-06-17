# Adaptive pairs trading with regime switching volatility detection

This notebook implements a dynamic pairs trading strategy using cointegration, volatility regime detection, and LSTM-based forecasting.

1)What It Does

Identifies pairs of financial stocks (e.g., JPM, BAC) with long-term relationships. Uses Kalman filter to estimate dynamic hedge ratios. Applies Hidden Markov Models to detect volatility regimes. Uses LSTM to forecast regime changes and adjust trading signals. Backtests the strategy with key metrics

2)Key Metrics (3-Year Backtest)

Sharpe Ratio: 0.87, CAGR: 42.5%, Total Return: 278.22%, Value at Risk (95%): –4.83%

3)How to Run

Install libraries: pip install yfinance pykalman hmmlearn scikit-learn statsmodels tensorflow pandas matplotlib. Open and run the notebook adaptive_pairs_trading.ipynb from top to bottom.

4)Notes

Includes data download, modeling, forecasting, and evaluation. Built for clarity and reproducibility in a single notebook. Suitable for research and demonstration
