# E-Commerce-Sales-Dashboard
Analyse E commerce sales data. Created a interactive dashboard using POWER BI

1. Introduction
2. 
In today’s digital marketplace, e-commerce platforms generate a large volume of transactional data every day. Analyzing this data is essential to understand customer behavior, sales performance, profitability, and operational efficiency.
This project focuses on designing an interactive E-Commerce Sales Dashboard using Power BI to transform raw transactional data into meaningful business insights.
The dashboard enables stakeholders to monitor key performance indicators (KPIs), identify trends, and make informed strategic decisions.

2. Objective of the Project

The main objectives of this project are:
To analyze overall sales, profit, and quantity trends
To identify top-performing states, categories, and customers
To track monthly profit fluctuations
To understand customer payment preferences
To present insights in a visually interactive manner using Power BI

3. The analysis is based on two structured CSV files, which together represent the sales lifecycle of an e-commerce business.
3.1 Orders Dataset (orders.csv)

This dataset contains order-level information and represents the transactional context of each purchase.

Provides descriptive attributes used for grouping, filtering, and slicing the data
Key Attributes:
Order ID – Unique identifier for each order
Order Date – Used for time-based analysis (month, quarter)
Customer Name – Used to analyze customer contribution
State – Used for geographical analysis
Category and Sub-Category – Used for product-level insights
Payment Mode – Used to study payment behavior

3.2 Details Dataset (details.csv)

This dataset contains quantitative and financial details related to each order.

Stores measurable values used for calculations and KPIs
Key Attributes:
Order ID – Used to link with orders table
Amount – Revenue generated per transaction
Quantity – Number of items sold
Profit – Net profit after costs
AOV (Average Order Value) – Indicates customer spending behavior

4. Key Performance Indicators (KPIs)
Sum of Amount :-Represents total revenue generated over the selected period.
Sum of Quantity :-Represents the total number of items sold.
Sum of Profit :-Represents total profitability.
Sum of AOV (Average Order Value) :-Measures average spending per order.

5. Visualization Theory and Analysis
5.1 Sales by State
Chart Type: Horizontal Bar Chart
Ideal for comparing values across regions
Easy to identify top and bottom performers

5.2 Quantity by Category
Chart Type: Donut Chart
Shows proportional contribution
Effective for category-wise distribution

5.3 Monthly Profit Analysis
Chart Type: Column Chart
Best for time-series comparison
Highlights growth and decline patterns

5.4 Sales by Customer
Chart Type: Bar Chart
Identifies high-value customers
Helps design loyalty programs

5.5 Quantity by Payment Mode
Chart Type: Donut Chart
Displays customer payment preferences
Helps optimize payment infrastructure

5.6 Profit by Sub-Category
Chart Type: Horizontal Bar Chart
Compares profitability across product types

5.7 Filters and Interactivity
The dashboard includes interactive slicers:
Quarter Filter (Q1–Q4) – Enables time-based comparison
State Filter – Enables regional performance analysis
