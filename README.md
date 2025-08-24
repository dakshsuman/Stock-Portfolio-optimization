# Stock-Portfolio-optimization

This project focuses on portfolio optimization using Monte Carlo simulation. Monte Carlo methods provide a powerful way to model uncertainty and assess risk by generating thousands of potential portfolio outcomes. This project demonstrates how to construct and evaluate an optimal portfolio by simulating different asset allocations, analyzing returns, and quantifying risk under varying market conditions


# Project Structure

Stock_data.csv - Contains historical price data of 30 Indian stocks over a 5-year period, extracted using the yfinance API. This dataset serves as the foundation for portfolio construction and optimization.

optimization.ipynb – A Jupyter Notebook implementing the complete workflow: data extraction from yfinance, exploratory data analysis and visualization, preprocessing of stock returns, portfolio analysis, and Monte Carlo–based portfolio optimization to identify risk-return efficient portfolios.
README.md: This file, providing an overview of the project.

# Data Collection

The data is fetched from historical stock data using the Yahoo Finance API and saves it as stock_data.csv in the 'data' directory. You can customize the stock symbol and date range as needed.

# Portfolio Analysis

The portfolio_analysis.py script calculates various portfolio metrics, such as mean returns, volatility, and correlation coefficients between assets. It also provides an option for Monte Carlo simulations.

# Optimization

The optimization.py script implements portfolio optimization techniques to construct an optimal portfolio. You can customize the optimization strategy and constraints according to your preferences. The optimized portfolio weights and metrics are saved as needed.

