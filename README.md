# Coffee-Day-Business-Expansion-Analysis
Comprehensive SQL retail analytics project solving 20 business case problems including churn analysis, time-series trends, product affinity, efficiency scoring, and composite city expansion ranking using advanced SQL (CTEs, window functions, normalization, ranking).

📌 **Project Overview**

This project is a comprehensive SQL-based retail analytics case study involving 20 business-driven analytical problems designed to simulate real-world Data Analyst scenarios.
The objective was to analyze multi-table transactional data and generate strategic insights across revenue performance, customer behavior, operational efficiency, and expansion planning.
The dataset contains 10,000+ sales records structured across four relational tables:

sales
customers
products
city

🎯 **Business Problems Solved**

The project covers the following analytical domains:

📊 **Revenue & Time-Series Analysis**
Monthly sales trend analysis
3-month moving average calculation
Quarter-wise performance evaluation
Growth rate computation using LAG()

👥 **Customer Behavior & Retention**

Customer churn detection (early buyers who stopped purchasing)
Active vs inactive customer segmentation
Customer base strength analysis

🏙️ **City-Level Performance**
Revenue per city
Revenue per customer
Rent-adjusted efficiency scoring
Ranking cities based on profitability metrics

🛒 **Product Insights**

Frequently purchased product pairs
Product performance by city and quarter
Product contribution to revenue

📈 **Advanced Business Modeling**

City Efficiency Score (Revenue / (Customers × Rent))
Composite Expansion Opportunity Score using weighted metrics:
Revenue (40%)
Customer base (30%)
Growth rate (20%)
Rent penalty (10%)
City ranking using DENSE_RANK()

🛠️ **SQL Concepts & Techniques Used**

Complex JOIN operations
CTEs (Common Table Expressions)
Window Functions:
LAG()
DENSE_RANK()
AVG() OVER()
Time-series analysis
Date functions (YEAR, MONTH, DATEPART)
Conditional aggregation
Behavioral filtering logic
Ranking & scoring models
