# Customer Shopping Behavior Analysis

## Overview
This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories.  
The objective is to uncover valuable insights into customer spending habits, subscription trends, product performance, and purchasing behavior to support strategic business decisions.

---

## Dataset Summary
- **Rows:** 3,900
- **Columns:** 18
- **Key Features:**
  - Customer demographics (Age, Gender, Location, Subscription Status)
  - Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
  - Shopping behavior (Discount Applied, Previous Purchases, Frequency, Review Rating, Shipping Type)

### Data Cleaning:
- Missing values handled in Review Rating column
- Column names standardized
- Feature engineering performed:
  - Age groups
  - Purchase frequency metrics
- Redundant columns removed
- Data prepared for SQL and dashboard analysis

---

## Tools & Technologies Used
- **Python**
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn
- **PostgreSQL**
- **SQL**
- **Power BI**
- **Jupyter Notebook**

---

## Project Workflow

### Data Loading
- Imported raw dataset using Pandas
- Performed initial inspection using:
  - `df.info()`
  - `df.describe()`

### Exploratory Data Analysis (EDA)
- Customer demographics analysis
- Revenue distribution
- Category-wise sales trends
- Product performance
- Subscription behavior
- Shipping type comparisons

### Data Cleaning
- Handled null values
- Standardized columns
- Removed duplicates
- Feature engineering
- Database integration with PostgreSQL

### SQL Business Analysis
Key SQL queries answered:
- Revenue by Gender
- High-Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Revenue
- Discount Dependency by Product
- Customer Segmentation
- Top Products by Category
- Repeat Buyer Subscription Trends
- Revenue by Age Group

### Power BI Dashboard
Created an interactive dashboard featuring:
- Total customers
- Average review ratings
- Average purchase amount
- Revenue by category
- Customer segmentation
- Subscription analysis
- Age group insights
- Sales performance

### Reporting & Presentation
- Business report created
- PowerPoint presentation structured
- Final recommendations included

---

## Key Insights
- Male customers generated higher revenue
- Young adults contributed the highest revenue
- Loyal customers formed the largest customer segment
- Subscribers showed consistent purchasing behavior
- Express shipping customers spent slightly more
- Certain products heavily relied on discounts

---

## Business Recommendations
- Increase subscription incentives
- Strengthen customer loyalty programs
- Optimize discount strategies
- Focus marketing on high-value customer segments
- Promote top-performing products

---

##  Project Structure

```
Bank-Loan-Analysis/
│
├── Customer_Shoppimg_Behaviour_Analysis.pdf
├── customer_shopping_behaviour_Analysis.ipynb
├── Customer_Behaviour_Dashboard.pbix
├── Customer_Shopping_Behaviour_Analysis.pptx
└── README.md

```

---


