# BANK-LOAN-ANALYTICS
An interactive Power BI dashboard that analyzes a bank's loan portfolio, tracking application volume, funding activity, repayment performance, and risk (good vs. bad loans) across borrower and loan attributes.
📊 Overview

The dashboard is built on a single financial_loan fact table and is organized into two report pages:

Dashboard (Summary) — KPI cards and breakdowns for a quick health check of the loan book
Overview — Deeper cuts of loan volume by borrower/loan characteristics and issuance trend over time
🔑 Key Metrics (KPI Cards)
Total Loan Applications
Total Funded Amount
Total Amount Received
Average Interest Rate
Average DTI (Debt-to-Income) Ratio
Good Loan % vs. Bad Loan % 
📈 Visuals & Breakdowns
Visual	Purpose
Clustered column charts	Funded amount, amount received & avg. interest rate by Loan Status; avg. DTI by Loan Status
Donut charts	Good vs. bad loan split; loan applications by Term
Clustered bar chart	Loan applications by Home Ownership
Treemap	Loan applications by Purpose
Line chart	Loan application trend over Issue Date
Slicers	Filter by Grade and Purpose
