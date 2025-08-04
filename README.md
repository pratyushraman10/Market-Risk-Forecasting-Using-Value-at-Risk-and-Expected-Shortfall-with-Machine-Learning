Project Title: Market Risk Forecasting Using Value-at-Risk and Expected Shortfall with Machine Learning

Overview:
This project implements a comprehensive market risk forecasting framework using historical simulation methods. It calculates portfolio Value-at-Risk (VaR) and Expected Shortfall (ES) based on daily historical returns of selected financial instruments. Designed with a professional finance environment in mind (e.g., BlackRock-style risk analytics), the project emphasizes model interpretability, replicability, and quantitative rigor.

Objective:
To assess and forecast potential portfolio losses under normal and extreme market conditions using data-driven statistical techniques.

Key Features:
- Historical price data retrieval using Yahoo Finance
- Portfolio construction using user-defined weights
- Daily returns calculation
- Value-at-Risk (VaR) estimation at 95% and 99% confidence levels
- Expected Shortfall (ES) calculation at the same levels
- Visualization of return distribution and risk thresholds
- Modular, scalable, and well-commented Python code
- Error handling for missing tickers, NaN values, and shape mismatches

Technologies Used:
- Python (NumPy, Pandas, Matplotlib, Seaborn)
- YFinance API for market data
- Risk quantification through non-parametric simulation

Use Case:
This project can be used by analysts, quants, and students to understand the impact of market movements on a portfolio. It can be extended into backtesting, Monte Carlo simulation, or ML-based forecasting for predictive risk analytics.

How to Run:
1. Install required libraries: `pip install yfinance pandas numpy matplotlib seaborn`
2. Edit the ticker list and portfolio weights in the script
3. Run the script in Jupyter Notebook or any Python IDE
4. Visualizations and printed metrics will appear as output

Future Work:
- Integration of stress testing and scenario analysis
- Incorporating macroeconomic indicators for predictive modeling
- Exporting metrics and plots to Power BI or interactive dashboards
- Backtesting VaR breaches using Kupiec or Christoffersen tests

Author: Pratyush Raman  
National Institute of Technology, Rourkela  
Date: August 2025
