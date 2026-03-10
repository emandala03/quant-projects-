# Quant Finance Projects

A collection of quick quant finance builds — made by a student who loves economics, markets, and getting his hands dirty with real data.

---

## Projects

### 1.  Value at Risk (VaR) Calculator
Measuring and comparing daily risk across different assets (Apple, Nvidia, US Bonds, Bitcoin) using two methods: Historical VaR and Parametric VaR. Highlights how extreme events like Bitcoin crashes expose the limits of purely mathematical risk models.

### 2.  Stock Price Prediction
Predicting Nvidia's next day closing price using three different models:  Linear Regression, Random Forest, and LSTM neural network. The project explores why model selection matters more than model complexity — Random Forest failed completely due to the extrapolation problem, while LSTM successfully followed the 2023 AI-driven price surge. Built with scikit-learn, TensorFlow/Keras, and yfinance. LSTM runs on Google Colab.

### 3.  Portfolio Optimization Tool
Selecting a basket of stocks and finding the optimal capital allocation that maximizes the Sharpe Ratio. Visualizes the Efficient Frontier to show the risk/return tradeoff. Built with PyPortfolioOpt.

### 4.  Monte Carlo Simulation for Options Pricing
Simulating 10,000+ random stock price paths using Geometric Brownian Motion to price options. Results are benchmarked against the Black-Scholes analytical formula.

### 5.  Pairs Trading Strategy Backtest
Identifying two cointegrated stocks (e.g. Coca-Cola & Pepsi), calculating their price spread, and backtesting a mean-reversion strategy: go long the underperformer and short the outperformer when the spread deviates beyond 2 standard deviations.

---

## Tools & Libraries
Python • Jupyter Notebook • yfinance • scikit-learn • PyPortfolioOpt • statsmodels • Backtrader • NumPy • Pandas • Matplotlib

---

## Status
Work in progress — new projects added weekly.
