# Stock-Portfolio-optimization

This project applies Monte Carlo Simulation to optimize a portfolio of Indian stocks. By simulating thousands of possible portfolio allocations, the project identifies portfolios that maximize risk-adjusted returns and minimize volatility, providing valuable insights for investment decision-making.

Project Overview

Extracted 5 years of historical stock data for 30 Indian companies using the yfinance API.

Conducted data exploration, preprocessing, and visualization to analyze stock trends, returns, and correlations.

Implemented Monte Carlo Simulation (10,000+ iterations) to generate random portfolio weights and assess performance.

# Evaluated portfolios using key metrics:

 Expected Returns

 Volatility (Risk)

 Sharpe Ratio (Risk-adjusted return)

# Identified:

 Maximum Sharpe Ratio Portfolio – Sharpe Ratio 1.05, Returns 22.7%, Volatility 15.2%

 Minimum Volatility Portfolio – Sharpe Ratio 0.85, Returns 17.9%, Volatility 13.2%
 
# Project Structure

stock_data.csv → Historical price data of 30 Indian stocks over a 5-year period.

optimization.ipynb → Jupyter Notebook containing:

Data extraction via yfinance

# Exploratory Data Analysis (EDA) & Visualization

Preprocessing & returns calculation

Monte Carlo Simulation for portfolio optimization

Risk-return visualization & analysis

# Tech Stack

Python

Libraries: pandas, numpy, matplotlib, seaborn, yfinance

# Key Results

Monte Carlo Simulation effectively modeled uncertainty by exploring 10,000+ portfolio outcomes.

Optimal portfolio achieved higher Sharpe Ratio and returns compared to equal-weighted strategies.

Demonstrated how quantitative finance techniques can balance risk and reward in real-world investment scenarios.

# Future Improvements

Integrate Value-at-Risk (VaR) and Conditional VaR for risk assessment.

Compare Monte Carlo results with deterministic optimization methods (e.g., convex optimization).

Extend to global stocks / sector-based portfolios.

# How to Run

Clone the repository
```
git clone https://github.com/your-username/monte-carlo-portfolio-optimization.git
cd monte-carlo-portfolio-optimization
```

Install dependencies
```
pip install -r requirements.txt
```

Run the Jupyter Notebook
```

jupyter notebook optimization.ipynb
```
