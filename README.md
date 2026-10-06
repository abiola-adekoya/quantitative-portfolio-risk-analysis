# Quantitative Portfolio Risk Analysis

A quantitative analysis of portfolio risk and performance using Python and financial market data.

## Project Overview

This project applies quantitative finance techniques to analyze portfolio performance, systematic and specific risk, volatility, and downside risk.

The analysis covers:

- Single-index model analysis
- Two-factor risk modeling
- Principal Component Analysis (PCA)
- Volatility modeling
- Monte Carlo simulation
- Value at Risk (VaR)

## Methodology

### 1. Single-Index Model

Analyzed the relationship between individual stock returns and market returns using regression analysis.

The analysis examines:
- Beta
- R-squared
- Annualized return
- Annualized volatility
- Portfolio beta

### 2. Two-Factor Risk Model

Decomposed portfolio risk into systematic and specific components using a two-factor framework.

### 3. Principal Component Analysis

Applied PCA to a broad set of equity returns to identify the main sources of common variation in the portfolio.

### 4. Volatility Modeling

Compared multiple approaches to measuring and modeling volatility, including:

- Unconditional volatility
- EWMA
- ARCH
- GARCH(1,1)

### 5. Monte Carlo Simulation

Simulated portfolio returns to evaluate potential outcomes and estimate downside risk.

### 6. Value at Risk

Estimated one-day Value at Risk using Monte Carlo simulation at a 99% confidence level.

## Key Results

- NVDA beta: **2.12**
- Goldman Sachs beta: **1.21**
- Equally weighted portfolio beta: **1.66**
- First principal component explained approximately **33.72%** of total variation
- First five principal components explained approximately **58.50%**
- Monte Carlo one-day 99% VaR: approximately **2.72%**

## Tools & Technologies

- Python
- Pandas
- NumPy
- Statistical modeling
- Regression analysis
- PCA
- ARCH/GARCH
- Monte Carlo simulation
- Value at Risk

## Author

**Abiola Adekoya**

MSc Finance | Quantitative Finance | Financial Analysis
