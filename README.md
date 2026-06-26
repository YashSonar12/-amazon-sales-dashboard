- Amazon E-Commerce Sales Analytics Dashboard
An end-to-end Power BI dashboard project analyzing Amazon India sales data for portfolio and job applications.

- Project Overview
This project analyzes 128,975 Amazon sales transactions to uncover revenue trends, top-performing categories, geographic sales patterns, and fulfilment insights using Microsoft Power BI.

- Business Questions Answered
Which product categories generate the most revenue?
Which states and cities are top performers?
How does revenue trend across months?
What is the split between Amazon vs Merchant fulfilment?
What is the order status breakdown (Shipped, Cancelled, Pending)?

- Tools & Technologies
ToolPurposePower BI DesktopDashboard creation & visualizationPower QueryData cleaning & transformationDAXCustom measures & calculationsMicrosoft Bing MapsGeographic visualization

- Dataset
Source: Kaggle — Amazon Sale Report
Records: 128,975 rows
Period: March–June 2022
Key Columns: Order ID, Date, Category, Qty, Amount, Ship State, Ship City, Status, Fulfilment

- Dashboard Pages
Page 1: Executive Dashboard
KPI Cards: Total Revenue, Total Orders, Total Qty, AOV
Monthly Revenue Trend (Line Chart)
Revenue by Category (Bar Chart)
Fulfilment Analysis (Donut Chart)
Order Status Breakdown (Bar Chart)
Interactive Slicers: Year, Month, Category

Page 2: Geographic Dashboard
State-wise Sales Map
Top States Bar Chart
City-wise Sales Analysis
State & Month Slicers

Page 3: Product Dashboard
Category Revenue (Donut Chart)
Size-wise Quantity (Bar Chart)
Category Orders (Treemap)
Category & Month Slicers

- Key DAX Measures
daxTotal Revenue = SUM(dataset[Amount])
Total Orders = DISTINCTCOUNT('dataset'[Order ID])
Total Qty = SUM(dataset[Qty])
AOV = DIVIDE([Total Revenue], [Total Orders])

- Key Insights
Set and Kurta are top revenue-generating categories
Maharashtra is the highest revenue state
Merchant fulfilment accounts for ~69% of orders
M and L sizes are most popular across all categories
Revenue peaked in April and declined toward June

- How to Use
Download the .pbix file
Open in Power BI Desktop (free download from Microsoft)
Use slicers to filter by Month, Category, or State
Click on any visual to cross-filter other charts
