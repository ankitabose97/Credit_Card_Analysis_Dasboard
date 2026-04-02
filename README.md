# Credit_Card_Analysis_Dashboard
## 📌 Overview

I built an end-to-end Power BI dashboard to analyze $57M in credit card transactions, identified that Blue card users and high-income segments drive most revenue, and analyzed weekly fluctuations including revenue drops. The dashboard provides insights into customer behavior, revenue trends, transaction patterns, and business performance for the year 2025.

It enables stakeholders to monitor key KPIs, identify high-performing segments, and track revenue fluctuations over time for better decision-making.

❗ Problem Statement

Financial institutions generate large volumes of transaction data but often struggle to extract meaningful insights.

This project aims to solve:

 - How to track and optimize revenue generation
 - How to understand customer spending behavior
 - How to identify high-value customer segments
 - How to analyze transaction trends and revenue fluctuations
 - How to detect revenue drops and performance gaps
 
🛠️ Tech Stack
- Power BI – Dashboard creation & data visualization
- SQL – Data extraction and querying
- Microsoft Excel – Data preprocessing
- DAX (Data Analysis Expressions) – Calculated measures and KPIs
  
🔄 Process
- Data Collection - Gathered customer, transaction, and card-related data from Kaggle in csv format
- Data Modeling - Created relationships between tables (customers, transactions)
- Created calculated metrics such as: - Revenue per customer, Current week revenue, Weekly revenue trends, WoW (Week-over-Week) growth
- Dashboard Development - Designed interactive dashboards with slicers (gender, income group, quarter)
- Built KPIs and visualizations: - Revenue trends, Customer segmentation, Transaction analysis
  
📈 Key Insights

Overview YTD:
  - Overall revenue is 57M
  - Total interest is 8M
  - Total transaction amount is 46M
  - Total 10K unique customers analyzed
  - Average Revenue per Customer: 5.49K
  - High-income groups generate a significantly larger share of total revenue
  - Male customers are contributing more in revenue, 31M, female 26M
  - Blue & Silver credit cards are contributing to 93% of the overall
WoW change:
  - Revenue increased by 28.8% in last week
Revenue Drop Analysis
  - Revenue dip observed in Week 52
  - Major decline driven by high-value customer segment
  - Indicates possible seasonal or behavioral drop in spending


📊 Transaction Insights
  - Total transactions: 667K
  - TX, NY & CA is contributing to 68%
  - Transaction volume increases across quarters, indicating growing engagement
  - Week-over-Week analysis shows fluctuations with notable dips (e.g., week 52)

(https://github.com/ankitabose97/Credit_Card_Analysis_Dasboard/blob/main/CC-%20Customers.png)

(https://github.com/ankitabose97/Credit_Card_Analysis_Dasboard/blob/main/CC-%20Transactions.png)
