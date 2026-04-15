# Portfolio Optimization and Equity Valuation using Python

## Overview

This project analyzes Indian equity markets by constructing and evaluating sector based portfolios and performing firm level valuation using Discounted Cash Flow. It combines quantitative finance, risk modeling, and valuation to generate practical investment insights.

## Objectives

* Construct sector based portfolios
* Compare risk and return characteristics
* Optimize portfolio weights
* Estimate downside risk using Value at Risk
* Simulate future price movements using Monte Carlo
* Perform intrinsic valuation using DCF

## Datasets

* Stock price data from Yahoo Finance
* Financial statement data from company annual reports
* Market benchmark data from Nifty 50

## Methodology

### Portfolio Analysis

* Moving averages for trend detection
* Equal weighted portfolio construction
* Expected return and volatility calculation
* Sharpe ratio for risk adjusted performance
* Efficient frontier using random portfolio generation
* Value at Risk at 95 percent confidence level
* Monte Carlo simulation using GBM and Cholesky decomposition

### Valuation Model

* Revenue forecasting using historical CAGR
* Free Cash Flow to Firm calculation
* Cost of equity using CAPM
* WACC estimation
* Terminal value using perpetual growth model
* Intrinsic value per share calculation

## Key Insights

### Portfolio Analysis

* Green portfolio delivered higher returns with superior Sharpe ratio
* Mixed portfolio achieved lower volatility due to diversification
* Brown portfolio showed weaker risk adjusted performance

### Valuation

* Most companies appear overvalued based on DCF results
* One stock shows strong undervaluation potential
* Higher beta increases WACC and reduces intrinsic value

## Project Structure

```
project-name/
│
├── data/
├── notebooks/
│   ├── portfolio_risk_analysis.ipynb
│   └── dcf_valuation_model.ipynb
│
├── outputs/
│   ├── charts/
│   └── results/
│
├── reports/
│   ├── portfolio_analysis_report.pdf
│   └── dcf_valuation_report.pdf
│
├── README.md
└── requirements.txt
```

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* SciPy
* Statsmodels
* yfinance

## How to Run

1. Clone the repository
2. Install dependencies using pip install -r requirements.txt
3. Open Jupyter Notebook
4. Run the notebooks in sequence

## Results Summary

* Portfolio optimization improved Sharpe ratio significantly
* Diversification reduced portfolio risk
* Monte Carlo simulation confirmed volatility patterns
* DCF valuation highlighted mismatch between price and fundamentals

## Future Improvements

* Include transaction costs and constraints in optimization
* Use advanced portfolio models
* Improve forecasting using machine learning
* Add real time data pipeline

## Author

Avinash Jha

