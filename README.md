# Portfolio Optimisation & Risk Analytics Using Python

A Python-based quantitative finance project applying Modern Portfolio Theory, portfolio optimisation techniques, and risk modelling methods to analyse and construct an optimal equity portfolio.

## Overview

This project develops a portfolio optimisation and risk analytics framework using three individual equities:

- Medtronic (MDT)
- Raytheon Technologies (RTX)
- S&P Global (SPGI)

The S&P 500 index (^GSPC) is used as a market benchmark to evaluate systematic risk and estimate stock sensitivity to market movements.

The objective of this project is to analyse risk-return characteristics, evaluate diversification benefits, construct optimal portfolios, and assess portfolio risk using the Single Index Model.

---
# Files

- [Portfolio Notebook](Portfolio.ipynb)
- [HTML Report](Portfolio.html)

---

# Data

Monthly stock price data is used to calculate returns and portfolio statistics.

Assets analysed:

- Medtronic (MDT)
- Raytheon Technologies (RTX)
- S&P Global (SPGI)
- S&P 500 Index (^GSPC)

The dataset is processed using Python, with monthly returns calculated from historical price observations.

---

# Key Methods

## Risk and Return Analysis

- Calculation of monthly and annualised returns
- Annualised volatility estimation
- Sharpe ratio calculation using a 3% annual risk-free rate
- Comparison of individual asset performance

## Correlation and Covariance Analysis

- Construction of covariance and correlation matrices
- Analysis of diversification benefits
- Evaluation of relationships between asset returns

## Portfolio Construction and Optimisation

- Minimum variance portfolio estimation
- Mean-variance optimisation framework
- Random portfolio simulation
- Opportunity set analysis
- Sharpe ratio optimisation

## Market Stress Testing

- COVID-19 market drawdown analysis
- Peak-to-trough decline measurement
- Recovery analysis

## Single Index Model

- CAPM-based regression against the S&P 500
- Estimation of:
  - Alpha (α)
  - Beta (β)
  - Idiosyncratic variance (σ²e)
  - R-squared
- Construction of Single Index Model covariance matrix
- Residual correlation analysis to evaluate model assumptions

---

# Key Findings

## Individual Asset Performance

- SPGI produced the strongest risk-adjusted performance with the highest Sharpe ratio (0.81) and annualised return (22.4%).
- RTX generated moderate returns (12.2%) but experienced higher volatility due to greater firm-specific risk.
- MDT displayed defensive characteristics with lower volatility but weaker risk-adjusted returns.

## Portfolio Optimisation

The minimum variance portfolio achieved:

- Expected annual return: **12.7%**
- Annual volatility: **17.8%**
- Sharpe ratio: **0.54**

The optimal allocation was:

- MDT: 50.9%
- RTX: 30.1%
- SPGI: 19.0%

The results demonstrate that diversification can reduce portfolio risk while maintaining attractive returns.

## Single Index Model Results

- SPGI had the highest market sensitivity with a beta of **1.15**, indicating greater responsiveness to market movements.
- MDT had the lowest beta (**0.85**), reflecting lower systematic risk.
- R-squared values ranged between **39% and 49%**, suggesting that market movements explain part, but not all, stock return variation.
- Residual correlations were generally low, providing support for the Single Index Model assumption while highlighting the importance of firm-specific factors.

---

# Tools and Libraries Used

## Programming

- Python

## Libraries

- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- scipy

## Financial Techniques

- Modern Portfolio Theory (Markowitz Optimisation)
- Sharpe Ratio Analysis
- CAPM Regression
- Single Index Model
- Risk-return modelling

---
