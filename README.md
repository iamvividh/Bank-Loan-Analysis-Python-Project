# Bank Loan Analysis Project

## Overview
This project analyzes a financial loan dataset using Python. It performs data exploration, calculates key performance metrics, and visualizes patterns related to loan applications, funding, repayments, borrower demographics, and risk assessment.  
The goal is to support data-driven decision-making for lending institutions.

## Dataset
- **Source:** financial_loan.xlsx  
- **Rows:** 38,576  
- **Columns:** 24  

**Key Columns**
- Loan Information: `loan_amount`, `total_payment`, `int_rate`, `dti`, `term`
- Borrower Details: `emp_length`, `emp_title`, `home_ownership`, `annual_income`
- Loan Status: `Fully Paid`, `Current`, `Charged Off`
- Other Attributes: `purpose`, `address_state`, `issue_date`

## Analysis Performed
1. **Summary Statistics**
   - Total loan applications
   - Funded amount and repayments
   - Average interest rate and DTI ratio  

2. **Loan Performance**
   - Good loan metrics (fully paid and current)
   - Bad loan metrics (charged off)

3. **Trend Analysis**
   - Monthly loan applications, funding, and repayments  

4. **Regional Insights**
   - State-wise distribution of funding and repayments  

5. **Segmented Analysis**
   - Loan term comparison (36 vs 60 months)
   - Employment length effect on loans
   - Loan purpose and distribution
   - Home ownership influence

## Key Findings
- **Total Loan Applications:** 38,576  
- **Total Funded Amount:** $435.76M  
- **Total Amount Received:** $473.07M  
- **Average Interest Rate:** 12.05%  
- **Average Debt-to-Income Ratio:** 13.33%  
- **Good Loans:** 86.18%  
- **Bad Loans (Charged Off):** 13.82%

## Visualizations
The notebook provides both static (Matplotlib, Seaborn) and interactive (Plotly) visualizations, including:
- Monthly trends in applications, funding, and repayments  
- Geographic distribution by U.S. states  
- Loan purpose and employment-based breakdowns  
- Loan term and home ownership comparisons

## Technology Stack
- **Python**
- **Libraries:** pandas, numpy, matplotlib, seaborn, plotly  

## Conclusion
The project demonstrates how exploratory data analysis can reveal trends in lending, repayment behavior, borrower risk profiles, and business insights. Such analysis can guide financial institutions in risk management and strategic decision-making.
