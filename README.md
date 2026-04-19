#Customer Shopping Behavior Analysis

 ---Overview---

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.
The goal is to uncover insights into customer spending patterns, product preferences, and subscription behavior to support data-driven business decisions.

---Dataset---

Rows: 3,900
Columns: 18
Data Includes:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Behavior metrics (Discount usage, Purchase frequency, Ratings, Shipping type)
Data Issue:
37 missing values in the Review Rating column
🛠️ Tools & Technologies
Python (Pandas, NumPy, Matplotlib, Seaborn)
PostgreSQL
Power BI
Jupyter Notebook
SQL

---Project Workflow---

1. Data Loading (Python)
Loaded dataset using Pandas
Checked structure using df.info() and summary stats using describe()
2. Exploratory Data Analysis (EDA)
Analyzed distributions and trends
Identified customer patterns and product behavior
Used visualizations (histograms, bar charts, correlations)
3. Data Cleaning & Preparation
Handled missing values using median imputation (category-wise)
Standardized column names (snake_case)
Created new features:
age_group
purchase_frequency_days
Removed redundant column (promo_code_used)
Ensured data consistency
4. SQL Analysis (PostgreSQL)

Cleaned data was loaded into PostgreSQL for business analysis.

Key queries included:

Revenue by gender
High-spending customers using discounts
Top 5 products by rating
Shipping type comparison (Standard vs Express)
Subscriber vs non-subscriber analysis
Discount-heavy products
Customer segmentation (New, Returning, Loyal)
Top products per category
Repeat buyers vs subscription behavior
Revenue by age group

---Dashboard (Power BI)---

An interactive dashboard was built to visualize insights.

Key Features:

KPI cards (Total customers, Avg rating, Avg purchase)
Revenue by category
Sales distribution
Age group analysis
Subscription insights
Filters for category, gender, and shipping type

(As shown in the dashboard on page 7 of the report)

---Key Results & Insights---
Male customers generated higher revenue compared to female customers
Express shipping users spent slightly more than standard users
Subscribers contributed significant revenue, but non-subscribers were larger in number
Certain products (e.g., hats, sneakers) had high discount dependency
Majority of customers fall into the “Loyal” segment
Young adults generated the highest revenue among age groups

(Insights derived from SQL outputs shown across pages 3–6)

---Business Recommendations---

Promote subscription benefits to increase recurring revenue
Implement loyalty programs for repeat customers
Optimize discount strategies to balance profit and sales
Highlight top-rated and best-selling products in campaigns
Target high-value age groups and frequent buyers
