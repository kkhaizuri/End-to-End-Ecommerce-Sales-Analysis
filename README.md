# End-to-End-Ecommerce-Sales-Analysis
This project analyzes e-commerce transaction data to uncover key business insights around revenue, profitability, and sales performance. The goal was to simulate a real-world data workflow—from raw data preparation to database design and interactive dashboard visualization.

## 🔧 Tools & Technologies
- Excel (Power Query – Transform)
- Microsoft SQL Server (MSSQL)
- Power BI

## 📁 Data Preparation

Raw transaction data (5,000+ records) was cleaned and transformed using Excel Power Query. This included:

- Handling missing and inconsistent values
- Removing duplicate records
- Standardizing date and categorical formats
- Creating calculated fields such as revenue, cost, and profit

These steps ensured the dataset was accurate, consistent, and ready for structured storage and analysis.

## 🗄️ Database Design (MSSQL)

A relational database was created in Microsoft SQL Server to store the cleaned data. Key steps included:

- Designing tables for transactions, products, and regions
- Importing cleaned data into SQL Server
- Writing SQL queries to join tables and aggregate metrics
- Extracting insights such as regional sales performance, top products, and discount impact

## 📈 Dashboard Development (Power BI)

An interactive Power BI dashboard was built to visualize business performance, featuring:

- KPI cards (Total Revenue, Profit, Profit Margin)
- Time-series analysis of sales trends
- Regional and product-level performance breakdowns
- Filters and slicers for dynamic exploration

## 💡 Key Insights
- Identified a 12% decline in profit margins linked to aggressive discounting strategies
- Found that certain regions had high sales volume but low profitability
- Highlighted top-performing products contributing most to revenue

## 🚀 Outcome

This project demonstrates an end-to-end data analytics workflow—combining data cleaning, database management, SQL querying, and data visualization—to generate actionable business insights and support data-driven decision-making.
