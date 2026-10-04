# 🚗 Automotive Sales Analytical Dashboard

## About This Project

This is my first Power BI portfolio project, created to practice data modeling, DAX measures, and dashboard design.

The dashboard analyzes automotive sales data and provides insights into revenue, customer performance, product performance, and sales trends through interactive visualizations.

---
## Dashboard Screenshot

dashboard.png<img width="1297" height="725" alt="dashboard png" src="https://github.com/user-attachments/assets/67eeddec-08a3-45fe-a311-c93dc92e728f" />


## Tools Used

- Power BI
- Power Query
- DAX

---

## Dataset

The project uses three tables:

### Fact_Sales
- deal_id
- line_no
- order_date
- customer_id
- product_id
- qty
- net_amount

### Dim_Customer
- customer_id
- customer_name
- market

### Dim_Product
- product_id
- product_name
- family
- unit_cost_euro

---

## Data Model

A star schema was created by connecting:

- Dim_Customer → Fact_Sales
- Dim_Product → Fact_Sales

This allowed easier analysis and better dashboard performance.

---

## KPIs Created

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Revenue Per Customer

---

## Dashboard Features

- Revenue by Vehicle Category
- Top 10 Products by Revenue
- Top 10 Customers by Revenue
- Revenue Trend Analysis
- Customer Revenue Table
- Interactive Filters

---

## Key Insights

- SUVs generated the highest revenue.
- Revenue increased over the selected period.
- A small group of customers contributed a large share of total revenue.
- Germany and France were the main markets.
- Product performance varied across categories.

---



---

## What I Learned

Through this project I practiced:

- Data Modeling
- Creating Relationships
- Writing DAX Measures
- Building KPI Cards
- Dashboard Design
- Business Analysis
- Power BI Reporting

---

## Business Recommendations

- SUVs are the strongest revenue driver and should remain a key focus area.
- Germany and France contribute most sales and represent the strongest markets.
- Top customers generate a large portion of revenue and should be targeted for retention campaigns.
- Revenue shows a positive growth trend from 2021 to 2024.

## Author

Created by an aspiring Data Analyst as part of my Power BI learning journey.
