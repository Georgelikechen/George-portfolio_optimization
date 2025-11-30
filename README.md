## Portfolio Optimization Project Overview

This project implements portfolio optimization automated workflow for 83 constituent stocks of the Hang Seng Index, aimed at testing different optimization strategies.

## Key Features

- **Data Acquisition**: Automatically download historical price data for Hang Seng Index constituent stocks
- **Portfolio Optimization Examples**:
  - Minimum Variance Optimization
  - Maximum Sharpe Ratio Optimization
  - Markowitz Efficient Frontier Optimization
- **Performance Evaluation**: Calculate expected returns, volatility, Sharpe ratio of optimized portfolios and other historical backtesting.

## Project Structure

```
George-portfolio_optimization/
├── data_query.ipynb          # Data acquisition script
├── optimization.ipynb        # Portfolio optimization core code
├── Hang_Seng_tickers.csv    # Hang Seng Index constituent stock list
├── data/                     # Historical price data directory
│   ├── 0001.HK.csv
│   ├── 0002.HK.csv
│   └── ...
└── README.md
```
