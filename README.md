# Bank Loan Dashboard 

**Interactive Power BI dashboard** showing bank loan KPIs: total applications, funded amount, received amount, interest rate, DTI, and drill-through pages (Summary, Overview, Details).

## Business Problem
Banks need to track loan portfolio performance, detect rising credit risk, and understand customer behavior across states, loan purposes, grades, and employment categories. Manual reporting slows decision-making and makes it difficult to identify trends such as increasing bad loans, high-risk grades, or changes in funded vs. received amounts.

## Goal of the Dashboard
Provide an interactive, real-time monitoring system for loan applications, funded amounts, collections, and risk indicators.
Enable quick comparison between good vs bad loans.
Give teams the ability to drill down into state-level, purpose-level, and customer-level insights.
Support management with clear KPIs for strategic and operational decisions.

## Key Visuals
KPI Cards: Total Loan Applications, Funded Amount, Amount Received, Avg Interest Rate, Avg DTI.
Donut Charts: Good vs Bad Loan distribution, Term distribution (36 vs 60 months).
Line Chart: Monthly trend of loan applications.
Map Visualization: Applications across states.
Bar Charts: By employment length, loan purpose, and home ownership.
Detailed Table: Loan-level view with filters for investigation (ID, Purpose, Grade, Issue Date, Funded Amount, Installment, etc.).

## Business Impact & Insights
Risk Identification: Highlights % of bad loans and their contributing factors (state, grade, purpose).
Performance Tracking: Shows how much loan amount is funded vs received, helping assess collection efficiency.
Customer Behavior Insights: Purpose-wise and employment-length insights reveal where demand is highest.
Geographical Insights: Map visual shows state-wise performance to guide regional strategies.
Operational Efficiency: Reduces manual reporting time and provides a single source of truth.

## Description
This Power BI project is an interactive dashboard designed to help credit risk teams, product managers, and business analysts monitor loan portfolio health and performance. It provides high-level KPIs and detailed drill-through pages so users can quickly view summary metrics and then dig into transaction-level details.

## Key Pages
Summary — Executive-style KPI cards (Total Loan Applications, Total Funded Amount, Total Amount Received, Avg Interest Rate, Avg DTI) and quick-good vs bad loan breakdown.
Overview — Visual analytics including monthly trends, geographic distribution (map), term split, loan purposes, employment length, and homeownership breakdown.
Details — Loan-level table with filters for deep investigation: ID, Purpose, Home Ownership, Grade, Issue Date, Funded Amount, Interest Rate, Installment, Amount Received.

## Features
- KPI cards: Total Loan Applications, Funded Amount, Amount Received, Avg Interest Rate, Avg DTI
- Visuals: trend by month, map, donut for term, bar charts for purpose and employment length, table details
- Filters: State, Grade, Purpose, Good vs Bad Loan

## Files
- `Dashboard/Bank_Loan_Report.pbix` — Power BI file (or link to shared file)
- `scripts/` — preprocessing and SQL/Python used
- `assets/` — screenshots and images

## Screenshots
![Summary](https://github.com/Samirpatra2050/Bank_Loan_Dashboard/blob/main/Bank_Loan_Report%20.png)
![Overview](https://github.com/Samirpatra2050/Bank_Loan_Dashboard/blob/main/Bank_Loan_Report%202.png)
![Details](https://github.com/Samirpatra2050/Bank_Loan_Dashboard/blob/main/Bank_Loan_Report%203.png)

## How to view
Download the .pbix file and open with Power BI Desktop.
Use the left navigation to switch between Summary, Overview, and Details pages.
Apply filters (State, Grade, Purpose, Good vs Bad Loan) to explore subsets.

## Tech stack
Power BI Desktop (DAX, Power Query)
Source data: CSV / SQL (preprocessed)

## Contact
👤 Samir Patra
📧 samirpatra2050@gmail.com
🔗 GitHub Profile
For questions or collaboration: https://github.com/<Samirpatra2050>/bank-loan-dashboard

