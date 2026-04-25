# Apple vs Microsoft: Which Stock Shows a Better Balance Between Return and Risk?

## Project Overview
This project compares Apple (AAPL) and Microsoft (MSFT) to examine which stock shows a better balance between return and risk using historical stock data retrieved from WRDS.

The project is designed as a simple and practical financial analysis for users who want to understand how two major technology stocks differ in terms of performance stability and risk-adjusted return.

## Problem Definition
Investors often care not only about return, but also about the risk taken to achieve that return. A stock with a high return may also involve high volatility or a large drawdown. Therefore, this project compares Apple and Microsoft from both return and risk perspectives to identify which stock provides a more balanced performance.

## Target Users
The intended users are:

- beginner investors
- students interested in financial markets
- users who want a simple comparison of two major technology stocks

## Data Source
This project uses historical stock data retrieved from **WRDS**.

- Source: WRDS
- Stocks analysed: Apple (AAPL) and Microsoft (MSFT)
- Variables used: historical prices / returns data
- Access date: *[Please add your actual access date here]*

> Note: If the raw dataset is not included in this repository due to access restrictions, users should retrieve the data directly from WRDS using their own account and follow the notebook instructions.

## Analytical Goals
The analysis focuses on the following indicators:

- **Daily Returns**  
  Measures day-to-day percentage changes in stock price.

- **Annualised Return**  
  Estimates the average yearly return of each stock.

- **Annualised Volatility**  
  Measures the yearly level of return fluctuation and risk.

- **Maximum Drawdown**  
  Captures the largest peak-to-trough decline over the sample period.

- **Return-Risk Ratio**  
  Compares return relative to volatility to evaluate risk-adjusted performance.

## Workflow
The Python workflow in this project includes:

1. Retrieving historical stock data from WRDS
2. Cleaning and preparing the dataset
3. Calculating daily returns
4. Computing annualised return, annualised volatility, maximum drawdown, and return-risk ratio
5. Visualising the comparison between Apple and Microsoft
6. Exporting the summary results as a CSV file

## Visualisations
This project includes bar charts for side-by-side comparison of key indicators:

- **Annual Return**
- **Annual Volatility**
- **Return-Risk Ratio**

These visualisations help users quickly compare the performance and risk characteristics of Apple and Microsoft.

## Output
The project exports the final summary table as:

- `apple_microsoft_risk_return_summary.csv`

This file can be used for further review, reporting, or inclusion in the GitHub repository.

## Key Findings
This notebook compares Apple and Microsoft from a return-risk perspective using historical stock data from WRDS.

The main indicators include:

- annualised return
- annualised volatility
- return-risk ratio
- maximum drawdown

Based on these metrics, the stock with the higher return-risk ratio and a more stable downside profile can be interpreted as the more balanced stock for beginner investors.

> Replace this section with your exact findings after running the notebook.  
> For example:  
> - Apple had a higher annualised return, but also higher volatility.  
> - Microsoft showed more stable performance with a lower drawdown.  
> - Overall, Microsoft/Apple offered a better balance between return and risk.

## Repository Structure
```text
.
├── notebook.ipynb
├── README.md
├── requirements.txt
└── apple_microsoft_risk_return_summary.csv
