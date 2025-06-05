# Banking-Risk-Analytics-Dashboard-using-Power-BI
Develop a basic understanding of risk analytics in banking and financial services, focusing on how data is used to minimize the risk of losing money while lending to customers.
# Banking Risk Analytics Dashboard using Power BI

## Problem Statement
Develop a basic understanding of risk analytics in banking and financial services, focusing on how data is used to minimize the risk of losing money while lending to customers.

## Solution
This project leverages Power BI to create interactive dashboards that assist banks in making informed lending decisions. The dashboards analyze the applicant’s profile to determine the likelihood of loan repayment, helping banks approve or reject loan applications effectively.

## Dataset Overview
The dataset consists of multiple interconnected tables containing client and banking details. The key tables include:
- Banking Relationship
- Client-Banking
- Gender
- Investment Advisor
- Period

These tables are linked using primary and foreign keys to enable comprehensive analysis.

## Data Cleaning and Feature Engineering
- **Engagement Timeframe:** Created a new column in the Client-Banking table indicating the timeline of the client's relationship with the bank.
- **Engagement Days:** Calculated the number of days the client has been with the bank (`DATEDIFF` function).
- **Income Band:** Categorized estimated income into bins (e.g., Low for < 100,000, Mid for < 300,000).
- **Processing Fees:** Processing fee rates are assigned based on the fee structure (e.g., high fee structure → 0.05 processing fee).

## Key Calculated Functions and Measures in Power BI
- **SUM:** Calculates total values (e.g., total bank deposits).
- **DISTINCTCOUNT:** Counts unique clients.
- **SUMX:** Sums an expression evaluated for each row (e.g., total fees = total loan * processing fees).
- **SWITCH:** Used for conditional calculations.
- **DATEDIFF:** Calculates duration between two dates (e.g., engagement days).

## Important KPIs and Metrics
- **Total Clients:** Number of unique clients.
- **Total Loan:** Sum of bank loan, business lending, and credit card balances.
- **Bank Loan:** The Total loan amount that clients need to repay.
- **Business Lending:** Loans given to small businesses.
- **Total Deposit:** Sum of all deposit accounts (bank deposit, savings, foreign currency, checking accounts).
- **Total Fees:** Charges for account setup and maintenance.
- **Credit Cards Balance:** Outstanding credit card amounts.
- **Engagement Length:** Total days of client engagement with the bank.

## Visualizations
- Home Dashboard
- Loan Analysis Dashboard
- Deposit Analysis Dashboard
- Summary Dashboard with key banking insights

## Conclusion
Power BI dashboards empower banking operations by providing real-time, actionable insights through effective data visualization of key banking metrics and KPIs. These tools assist in risk minimization, customer segmentation, and strategy formulation in the financial sector.

## Future Work
- Extend analysis to include loan default prediction models.
- Enhance dashboards with customer segmentation by demographics and income.
- Provide competitive insights for banks to strategize client acquisition.
- Analyze loan distribution across different nationalities and bank types.
- Integrate additional data sources for a 360-degree customer view.

---

*This project demonstrates the power of data analytics in optimizing risk and operational efficiency in banking through interactive Power BI dashboards.*

