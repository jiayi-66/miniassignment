# Apple vs Microsoft: A Comparative Analysis of Return and Risk for Beginner Investors

## Project Overview
This project compares Apple (AAPL) and Microsoft (MSFT) using historical stock market data from Yahoo Finance. The aim is to examine how the two stocks differ in terms of return and risk, and to provide a simple, data-based interpretation for beginner investors and students interested in financial markets.

This repository contains the full Python analysis workflow, including data collection, cleaning, calculation of return and volatility metrics, visualisation, and interpretation of results.

## Problem Statement
Many beginner investors are interested in major technology stocks, but it can be difficult to understand whether a stock with stronger growth is also taking on more risk. This project addresses that problem by comparing Apple and Microsoft across key return and risk indicators over a selected time period.

The project focuses on a practical question: which stock appears to offer a better balance between return and risk for beginner investors?

## Target Users
This project is designed for:
- beginner investors
- university students learning finance, investment, or data analysis
- users who want a simple comparison of two major technology stocks before making investment-related decisions

## Research Question
### Main Question
How do Apple and Microsoft compare in terms of return and risk, and which stock appears to offer a better balance for beginner investors?

### Sub-questions
- Which stock generated a higher cumulative return over the selected period?
- Which stock showed greater day-to-day volatility?
- Does higher return appear to be associated with higher risk?
- Which stock appears more stable for users with lower risk tolerance?

## Data Source
- **Source:** Yahoo Finance
- **Tickers:** AAPL, MSFT
- **Data type:** Historical daily stock price data
- **Time period:** [Insert your selected start date] to [Insert your selected end date]
- **Access date:** [Insert date]
- **Key variables:** Date, Open, High, Low, Close, Adjusted Close, Volume

This project uses publicly accessible financial data suitable for educational analysis. The source and access date are clearly stated to support transparency and reproducibility.

## Analytical Workflow
The project follows the workflow below:
1. Retrieve historical stock data for Apple and Microsoft
2. Inspect and clean the dataset
3. Calculate daily returns and cumulative returns
4. Measure and compare volatility as a simple indicator of risk
5. Visualise price movement, return patterns, and risk-return differences
6. Interpret the findings for beginner investors

## Tools and Libraries
Main tools used in this project:
- Python
- pandas
- numpy
- matplotlib
- seaborn
- yfinance

## Repository Structure
```text
README.md
notebooks/
  analysis.ipynb
figures/
  price_trend.png
  cumulative_return.png
  volatility_comparison.png
  risk_return_summary.png
data/
  [optional: only include small files if used]
requirements.txt
