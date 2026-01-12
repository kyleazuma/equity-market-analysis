# Equity Market Analysis

A personal Python project for **exploratory equity market analysis and portfolio backtesting** using historical stock data.

This project applies:
- Market data collection and cleaning
- Return and risk computation
- Performance, volatility, drawdown, and correlation analysis
- Equal-weight portfolio backtesting

---

## Overview

The analysis focuses on large-cap US technology stocks:

- **GOOGL**
- **AMZN**
- **AAPL**
- **META**
- **NVDA**
- **TSLA**

**Time period:** January 2020 – October 2025  
**Data source:** Yahoo Finance (`yfinance`)

---

## Key Components

### Data
- Daily adjusted prices
- Cleaned and aligned time series

### Metrics
- Daily and annualized returns
- Annualized volatility
- Summary statistics

### Analysis
- Cumulative and indexed performance
- Moving averages (20-day, 50-day)
- Rolling 30-day annualized volatility
- Drawdowns (peak-to-trough)
- Correlation matrix

### Portfolio
- Equal-weight portfolio
- Cumulative performance
- Annual return, volatility, Sharpe ratio
- Comparison vs individual stocks

### Visualization
- Static plots: Matplotlib, Seaborn
- Interactive plots: Plotly

---

## Project Structure

```
equity-market-analysis/
│
├── equity_market_analysis.py
├── README.md
```
