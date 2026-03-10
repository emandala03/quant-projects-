# Data Sources

This file documents all data sources used across the five projects 
in this repository.

---

## Project 1 — VaR Calculator

| Asset | Ticker | Source | Period |
|-------|--------|--------|--------|
| Apple | AAPL | Yahoo Finance via yfinance | 2020-2024 |
| Nvidia | NVDA | Yahoo Finance via yfinance | 2020-2024 |
| US Bonds ETF | TLT | Yahoo Finance via yfinance | 2020-2024 |
| Bitcoin | BTC-USD | Yahoo Finance via yfinance | 2020-2024 |

---

## Project 2 — Stock Price Prediction

| Asset | Ticker | Source | Period |
|-------|--------|--------|--------|
| Nvidia | NVDA | Yahoo Finance via yfinance | 2020-2024 |

Training period: 2020-2022
Test period: 2023

---

## Project 2b — LSTM

| Asset | Ticker | Source | Period |
|-------|--------|--------|--------|
| Nvidia | NVDA | Yahoo Finance via yfinance | 2020-2024 |

Training period: 2020-2022
Test period: 2023

---

## Project 3 — Portfolio Optimization

| Asset | Ticker | Source | Period |
|-------|--------|--------|--------|
| Apple | AAPL | Yahoo Finance via yfinance | 2020-2024 |
| Nvidia | NVDA | Yahoo Finance via yfinance | 2020-2024 |
| JPMorgan Chase | JPM | Yahoo Finance via yfinance | 2020-2024 |
| Johnson & Johnson | JNJ | Yahoo Finance via yfinance | 2020-2024 |
| US Bonds ETF | TLT | Yahoo Finance via yfinance | 2020-2024 |
| Microsoft | MSFT | Yahoo Finance via yfinance | 2020-2024 |
| ExxonMobil | XOM | Yahoo Finance via yfinance | 2020-2024 |
| Gold ETF | GLD | Yahoo Finance via yfinance | 2020-2024 |
| Amazon | AMZN | Yahoo Finance via yfinance | 2020-2024 |
| UnitedHealth | UNH | Yahoo Finance via yfinance | 2020-2024 |

---

## Project 4 — Monte Carlo Options Pricing

| Parameter | Value | Source |
|-----------|-------|--------|
| Stock Price (S0) | $185 | Yahoo Finance — AAPL closing price, January 2024 |
| Risk-free Rate (r) | 5% | US Treasury 1-Year Yield, January 2024 — Federal Reserve Economic Data (FRED) |
| Volatility (sigma) | 28% | AAPL historical volatility 2020-2024, computed via yfinance |
| Strike Price (K) | $195 | Set ~5% above current price — standard out-of-the-money convention |
| Time to Expiry (T) | 1 year | Standard didactic convention |

**External references:**
- FRED database: https://fred.stlouisfed.org
- Investopedia Monte Carlo: https://www.investopedia.com/terms/m/montecarlosimulation.asp

---

## Project 5 — Pairs Trading Strategy Backtest

| Asset | Ticker | Source | Period |
|-------|--------|--------|--------|
| Coca-Cola | KO | Yahoo Finance via yfinance | 2018-2024 |
| PepsiCo | PEP | Yahoo Finance via yfinance | 2018-2024 |

**External references:**
- Backtrader documentation: https://www.backtrader.com
- Statsmodels cointegration: https://www.statsmodels.org

---

## General Notes

All price data was downloaded using the yfinance Python library with 
auto_adjust=True to account for stock splits and dividend adjustments.
All data is used strictly for educational and research purposes.
