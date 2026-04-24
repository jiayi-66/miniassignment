# Apple vs Microsoft: Which Stock Shows a Better Balance Between Return and Risk?

## Project Overview
This project compares Apple (AAPL) and Microsoft (MSFT) to examine which stock shows a more balanced performance between return and risk.

The analysis is designed for **beginner investors** and **students interested in financial markets** who want a simple and interpretable comparison of two major technology stocks.

## Research Question
**Which stock, Apple or Microsoft, shows a more balanced performance between return and risk?**

## Target User
- Beginner investors
- Students interested in stock market analysis
- Users who want a basic comparison of return and risk in large technology stocks

## Business Relevance
This project is business-related because stock performance analysis is valuable for investment decision-making.  
Comparing return and risk can help users better understand how different assets may suit different investment preferences.

## Data Source
- **Source:** WRDS
- **Companies analysed:** Apple (AAPL) and Microsoft (MSFT)
- **Time period:** 2021-01-01 to 2025-01-01
- **Access date:** [Please replace with your actual access date]

> Note: The notebook uses WRDS data access. The exact WRDS library name, table name, and field names may vary depending on database access permissions and should be checked before running the code.

## Project Files
- `apple_microsoft_wrds_analysis.ipynb` – Jupyter Notebook containing the full analysis
- `apple_microsoft_risk_return_summary.csv` – exported summary table
- `requirements.txt` – required Python packages
- `README.md` – project introduction and usage guide

## Methods
This project uses Python for data retrieval, cleaning, analysis, and visualisation.

Main analytical steps:
1. Connect to WRDS
2. Retrieve stock data for Apple and Microsoft
3. Clean and prepare the dataset
4. Calculate key performance indicators:
   - mean daily return
   - daily volatility
   - annualised return
   - annualised volatility
   - return-risk ratio
   - maximum drawdown
5. Visualise cumulative returns and key return-risk indicators
6. Export the summary table as a CSV file

## Key Metrics Explained
- **Annualised Return:** estimated yearly return based on average daily return
- **Annualised Volatility:** estimated yearly risk based on daily return fluctuations
- **Return-Risk Ratio:** annualised return divided by annualised volatility
- **Maximum Drawdown:** the largest peak-to-trough decline during the sample period

A stock with a higher return-risk ratio and a smaller maximum drawdown may be considered more balanced between return and risk.

## Key Findings
This project compares Apple and Microsoft using several return-risk indicators.  
The final result depends on the calculated outputs in the notebook, especially:
- annualised return
- annualised volatility
- return-risk ratio
- maximum drawdown

The stock with the stronger overall balance across these metrics is interpreted as the more balanced choice for the target user.

> Please update this section after running the notebook and checking the final results.

Example:
- Microsoft showed lower volatility and a more stable drawdown profile.
- Apple achieved stronger return growth over some periods.
- Based on the return-risk ratio, **[replace with your actual result]** appeared to provide the more balanced performance.

## Visual Outputs
The notebook includes:
- cumulative return line chart
- bar chart of annual return
- bar chart of annual volatility
- bar chart of return-risk ratio

These visualisations help users compare performance and downside risk more clearly.

## How to Run the Project

### 1. Clone or download the repository
```bash
git clone [your-repository-link]
