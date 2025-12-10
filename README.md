# SPY ML Trading algo.1

This project analyzes SPY using multiple technical indicators and a machine learning model to evaluate how different strategies perform across various market environments. It includes data retrieval, feature engineering, backtesting, model training, and performance comparison using standard quantitative metrics.


## Strategies Implemented

### Technical Indicator–Based Strategies
- MA10/MA50 Moving Average Crossover
- RSI Strategy
- MACD Strategy
- Bollinger Bands Strategy
- Stochastic Oscillator Strategy

### Machine Learning Strategy
- Linear Regression model predicting next-day SPY returns  
- Train/test split  
- RMSE and R² evaluation  
- Long/flat strategy based on model predictions


## Performance Metrics

Each strategy is evaluated using:

- CAGR (annualized return)
- Volatility
- Max Drawdown
- Sharpe Ratio

These metrics help compare strategies not only on returns but on risk and stability.

---

## Data Sources

All market data is retrieved using yfinance, including:
- SPY (S&P 500)
- Global indices (AORD, N225, HSI, GDAXI, CAC40, FCHI, GSPC, DJI, IXIC)

## Technologies Used

- Python  
- pandas  
- numpy  
- matplotlib  
- yfinance  
- scikit-learn  
- ta  

Dependencies are listed in `requirements.txt`.

## How to Run the Project

1. Install required packages
2. Open the Jupyter notebook
3. Run all cells from top to bottom to:
- Download data  
- Compute technical indicators  
- Train the ML model  
- Generate strategy returns  
- Evaluate performance  

## Purpose of the Project

This project demonstrates:
- Quantitative trading strategy design  
- Technical indicator engineering  
- Machine learning model training and evaluation  
- Backtesting methodology and performance benchmarking  
- Understanding how strategies behave across different market regimes  
- Building a complete data pipeline from raw price data to actionable signals  
- Evaluating results using risk-adjusted metrics (CAGR, volatility, Sharpe Ratio, max drawdown)

## Contact:cuccuiniryan0@gmail.com


