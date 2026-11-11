# PSX Portfolio Risk Analysis: VaR and CVaR

# Project Overview

This project examines portfolio downside risk using selected equities listed on the Pakistan Stock Exchange (PSX).
Using historical stock price data, the analysis estimates Value at Risk (VaR) through three approaches: Historical Simulation, Parametric VaR and Monte Carlo Simulation. It also estimates Conditional Value at Risk (CVaR) to examine expected portfolio losses beyond the VaR threshold.

# Methodology

The project covers:

- Historical stock price retrieval using Yahoo Finance.
- Calculation of daily logarithmic returns.
- Construction of an equally weighted portfolio.
- Estimation of portfolio risk over a five-day holding period.
- Historical Simulation VaR.
- Parametric VaR using portfolio volatility and the normal distribution.
- Monte Carlo simulation using 10,000 simulated scenarios.
- Estimation of Conditional Value at Risk (CVaR).
- Comparison and visualization of portfolio loss distributions.

# Risk Measurement Parameters

- Portfolio value: PKR 1,000,000
- Holding period: 5 trading days
- Confidence level: 90%, 95%, 99%
- Monte Carlo simulations: 10,000

# Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- yfinance.

# Data

Historical stock price data is retrieved through Yahoo Finance for selected PSX-listed equities.

# Repository Contents

PSX_Portfolio_Risk_Analysis.ipynb – Complete Python implementation and analysis.

# Disclaimer

This project is for educational and research purposes only. VaR and CVaR estimates are model-dependent and should not be interpreted as guarantees of maximum potential losses.
