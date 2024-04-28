# Ridge Regression Portfolio Management

This project demonstrates the use of Ridge Regression for portfolio management with a simple trading strategy. It fetches historical stock data from Yahoo Finance and performs a series of analyses, including backtesting, calculation of portfolio returns, and performance metrics such as Sharpe ratio and drawdowns.

## Features

- Fetch historical stock data from Yahoo Finance.
- Perform data preprocessing and feature generation.
- Implement Ridge Regression with GridSearchCV to find the optimal regularisation parameter.
- Backtest the regression model with a simple trading strategy.
- Calculate portfolio returns, Sharpe ratio, and drawdowns.
- Output formatted performance metrics, including ROI.

## Requirements

- Python 3.6 or later.
- The following Python packages: `yfinance`, `pandas`, `numpy`, `sklearn`, `matplotlib`.

## Usage

1. Clone or download this repository.
2. Install the required packages using `pip install -r requirements.txt` or manually.
3. Run the script to fetch historical stock data and perform analysis.
4. Review the outputs for portfolio management insights and performance metrics.

## Performance Metrics

- **Sharpe Ratio**: A measure of risk-adjusted return, calculated using excess returns and the standard deviation of returns.
- **Drawdowns**: The difference between the maximum portfolio value and the current value.
- **ROI**: The return on investment, calculated as a percentage of the initial portfolio value.

