# Financial Risk Analysis

## Project Overview
This project analyzes customer loan data to identify financial risks and default patterns. It is designed to assist in making data-driven lending decisions.

## Objective
- Identify risky customers.
- Determine key factors causing loan defaults.
- Provide actionable business insights.

## Tech Stack
- **Language**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
- **Tool**: Jupyter Notebook

## Dataset
The dataset `data/loan_data.csv` contains synthetic but realistic banking data with columns:
- `Customer_ID`: Unique identifier
- `Age`: Customer age
- `Income`: Annual income
- `Loan_Amount`: Requested loan amount
- `Credit_Score`: Credit trustworthiness score
- `Loan_Status`: Target variable (Paid / Default)

## Key Insights
1. **Credit Score is Critical**: Customers with credit scores below 600 have a >50% default rate.
2. **Income Correlation**: Lower income groups are more susceptible to default, especially for high loan amounts.
3. **Actionable Insight**: Stricter approval criteria should be applied for high-loan-to-income ratio applicants.

## How to Run
1. Install dependencies: `pip install -r requirements.txt`
2. Open the notebook: `jupyter notebook analysis.ipynb`
3. Run all cells to view the analysis.

---
*Created for Deloitte New Level Analyst (NLA) Role Assessment*
