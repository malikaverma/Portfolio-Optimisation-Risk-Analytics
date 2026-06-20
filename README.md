# Portfolio Optimisation - Risk-Analytics Using Python
Python-based portfolio optimisation and risk analytics framework applying Modern Portfolio Theory, Sharpe ratio analysis, and quantitative risk modelling.

# Overview
This project applies quantitative finance methods to analyse and optimise a portfolio consisting of three equities:
- Medtronic (MDT)
- Raytheon Technologies (RTX)
- S&P Global (SPGI)

The S&P 500 index is used as a benchmark for market performance.

The objective is to evaluate risk-return characteristics, assess diversification benefits, and construct an optimal portfolio using Modern Portfolio Theory.

--------------------------------------------------------------------------------------------------------------------------------------------

# Key Methods

Risk and Return Analysis
- Calculation of monthly and annualised returns
- Estimation of annualised volatility
- Sharpe ratio computation for risk-adjusted performance

Correlation and Covariance Analysis
- Construction of covariance and correlation matrices
- Analysis of inter-asset relationships
- Rolling correlation analysis with the market index

Portfolio Construction and Optimisation
- Minimum variance portfolio estimation
- Efficient frontier simulation
- Mean-variance optimisation framework

Market Stress Testing
- COVID-19 drawdown analysis
- Peak-to-trough decline measurement and recovery assessment

Single Index Model
- Regression of asset returns against the S&P 500
- Estimation of alpha, beta, and R-squared
- Decomposition of systematic and idiosyncratic risk

--------------------------------------------------------------------------------------------------------------------------------------------

# Key Findings

- SPGI exhibited the highest risk-adjusted performance, reflected in its Sharpe ratio
- RTX demonstrated the highest volatility due to cyclical exposure to the aerospace sector
- MDT acted as a defensive asset, reducing overall portfolio volatility
- Diversification across the three assets significantly reduced portfolio risk
- The optimised portfolio improved risk-adjusted returns relative to individual assets

--------------------------------------------------------------------------------------------------------------------------------------------

# Tools and Libraries Used

- Python (pandas, numpy, matplotlib)
- Microsoft Excel (data sourcing and preprocessing)
- Financial econometrics techniques including Modern Portfolio Theory and CAPM-based regression analysis
