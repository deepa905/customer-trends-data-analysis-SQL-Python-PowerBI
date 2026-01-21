**Customer Shopping Behavior Analysis**


**Project Overview**

This project analyzes customer shopping behavior using transactional data to identify revenue drivers, discount usage patterns, and the impact of subscriptions on customer spending. The objective is to support data-driven business decisions related to marketing strategy, promotions, and customer engagement.

The project demonstrates an end-to-end data analytics workflow using Python, SQL, and Power BI.

**Business Objective**

To answer key business questions such as:

1. Which customer and product attributes drive revenue?

2. How effective are discounts in influencing purchase behavior?

3. Do subscribed customers spend more than non-subscribers?

4. How do operational factors like shipping type affect spending?

**Dataset Summary**

Records: 3,900 transactions

Features: 18 columns

Data Type: Transaction-level retail data

Key attributes include:

Customer demographics (Age, Gender, Location)

Purchase details (Category, Item, Purchase Amount)

Engagement indicators (Previous Purchases, Subscription Status)

Promotions (Discount Applied)

Operations (Shipping Type, Payment Method)

Customer feedback (Review Rating)

**Tools & Technologies**

Python: pandas, matplotlib, seaborn (EDA & data preparation)

SQL: PostgreSQL (business-driven queries)

Power BI: Interactive dashboard & KPIs

Version Control: GitHub

**Analysis Workflow**
1. Data Preparation & EDA (Python)

Cleaned and validated the dataset

Handled missing values in review ratings

Performed exploratory analysis to understand spending patterns

Identified that customer behavior is non-linear and segment-driven

2. Business Analysis (SQL)

SQL queries were written to answer business questions such as:

Revenue contribution by gender and age group

High-value customers despite discounts

Top-rated and most purchased products

Subscription vs non-subscription spending

Discount dependency across products

3. Visualization & Insights (Power BI)

Designed a one-page dashboard with:

KPI cards (Revenue, Avg Spend, % Subscribers, % Discounted Transactions)

Revenue and spending breakdowns

Discount and subscription impact analysis

Dashboard visuals respond dynamically to filters

**Key Insights**

Revenue is driven primarily by product category, not age

Discounts increase transaction frequency but not significantly transaction value

Subscriptions support engagement rather than higher per-transaction spend

Faster shipping options show slightly higher average purchase values

Customer behavior is better explained through grouped analysis than linear trends

**Business Recommendations**

Optimize discount usage to avoid unnecessary margin loss

Focus subscription strategies on engagement rather than price reductions

Prioritize high-revenue categories in marketing and inventory planning

Promote faster shipping options for higher-value transactions
