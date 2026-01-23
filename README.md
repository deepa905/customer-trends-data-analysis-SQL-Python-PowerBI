**Customer Shopping Behavior Analysis**

***End-to-End Data Analyst Project (Python | SQL | Power BI)***

📌 Project Overview

This project analyzes customer shopping behavior using transactional data to identify revenue drivers, discount usage patterns, and the impact of subscriptions on customer spending.
The objective is to support data-driven business decisions related to marketing strategy, promotions, and customer engagement.

This repository demonstrates a complete end-to-end data analytics workflow, covering data exploration, business analysis, and dashboard-based storytelling.

🎯 Business Problem

Businesses often struggle to understand:

Which customer and product attributes contribute most to revenue

Whether discounts actually increase spending

How subscription status affects customer behavior

How operational factors (shipping, seasonality) influence purchases

Key Question:

How can customer shopping data be used to uncover meaningful patterns and support better business decisions?

🧩 Dataset Summary

Records: 3,900 transactions

Columns: 18

Data Type: Transaction-level retail data

Key attributes include:

Customer demographics (Age, Gender, Location)

Purchase details (Category, Item Purchased, Purchase Amount)

Engagement indicators (Previous Purchases, Subscription Status)

Promotions (Discount Applied)

Operations (Shipping Type, Payment Method)

Customer feedback (Review Rating)

Data Quality Note:
The dataset was largely clean, with minimal missing values in review ratings. Basic data quality checks were performed before analysis.

🛠️ Tools & Technologies

Python: pandas, matplotlib, seaborn (EDA & data preparation)

SQL: PostgreSQL (business-driven queries)

Power BI: Interactive dashboard & KPIs

Version Control: GitHub

🔍 Analysis Workflow

1️⃣ Data Preparation & Exploratory Analysis (Python)

Checked for missing values, duplicates, and data types

Performed exploratory analysis to understand distributions and patterns

Created derived features (e.g., age groups) for better interpretability

Key observation:
Customer spending behavior is non-linear and varies significantly across categories and transaction attributes rather than showing simple linear trends.

2️⃣ Business Analysis (SQL)

SQL queries were written to answer specific business questions such as:

Revenue contribution by gender and age group

Identification of high-spending customers using discounts

Comparison of average spend across shipping types

Subscription vs non-subscription spending

Products with high discount dependency

Top products within each category

The focus was on clear aggregation logic and business interpretation rather than complex SQL constructs.

3️⃣ Visualization & Insights (Power BI)

A one-page Power BI dashboard was designed to present insights clearly for stakeholders.

Dashboard Highlights:

KPI Cards

Total Revenue

Total Customers

Average Spend per Transaction

% Subscribers

% Discounted Transactions

Key Visuals

Revenue by product category

Revenue by age group

Average spend by subscription status

Discount applied vs purchase amount

Shipping type vs average spend

Filters

Category, Age Group, Season, Subscription Status, Shipping Type

All visuals and KPIs update dynamically based on filters.

📊 Key Insights

Revenue is driven primarily by product category, not customer age

Discounts increase transaction frequency but do not significantly increase transaction value

Subscribed customers do not spend more per transaction, but contribute to consistent engagement

Faster shipping options show slightly higher average purchase values

Customer behavior is better explained through grouped analysis than linear trends

✅ Business Recommendations

Optimize discount usage by avoiding blanket promotions and focusing on price-sensitive products

Position subscriptions as engagement tools rather than price-reduction mechanisms

Prioritize high-revenue categories for marketing and inventory planning

Promote faster shipping options for higher-value customer segments

🚀 Future Enhancements

Time-series trend analysis

Customer lifetime value (CLV)

Repeat-purchase or churn analysis

A/B testing of discount strategies

🧠 Key Learnings

Translating business questions into analytical workflows

Handling real-world, transaction-level data

Designing KPI-driven dashboards

Integrating Python, SQL, and Power BI into a cohesive analytics project

Communicating insights clearly to non-technical stakeholders
