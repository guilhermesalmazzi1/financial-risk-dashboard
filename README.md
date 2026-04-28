# financial-risk-dashboard
Data-driven dashboard for credit risk, customer behavior, and revenue analysis.

# Buy Now Pay Later (BNPL) - Revenue & Credit Risk Analysis
This project features an interactive dashboard developed in Power BI to monitor and analyze the performance of a Buy Now Pay Later (BNPL) financial operation. The primary focus is the intersection between commercial revenue and credit risk management, providing a clear view of the portfolio's financial health.

The fictional dataset contains detailed information on transactions, demographic profiles, credit score indicators, and repayment history.

# Dashboard Structure 📊
The report is organized into three strategic pages to support data-driven decision-making:

1. Executive & Performance:

Key KPIs: Total Revenue, Average Ticket, and Overall Default Rate.

Sales volume analysis by product category and geographic location.

2. Customer Profile (Demographics):

Segmentation by occupation (employment_type) and income brackets.

Engagement analysis based on app usage frequency.

3. Risk & Delinquency Management:

Correlation between risk_score and debt_to_income_ratio.

Monitoring of repayment delay days and missed payments.

Default analysis (default_flag) by customer segment.


# Technologies and Processes (ETL) 🛠️
The following data science techniques and tools were applied:

ETL with Power Query: Raw data (CSV) processing, including regionalization fixes (decimal point vs. comma), category standardization, and null value handling.

Modeling with DAX: Creation of calculated measures for percentage rates and aggregated metrics.

Data Visualization: Application of UI/UX best practices for data (alignment, color palettes, and typography) to ensure a fluid data storytelling experience.

