Amazon E-Commerce Sales Analytics Dashboard

> An end-to-end Power BI dashboard project analyzing Amazon India sales data for portfolio and job applications.

Project Overview
This project analyzes **128,975 Amazon sales transactions** to uncover revenue trends, top-performing categories, geographic sales patterns, and fulfilment insights using **Microsoft Power BI**.

Business Questions Answered
- Which product categories generate the most revenue?
- Which states and cities are top performers?
- How does revenue trend across months?
- What is the split between Amazon vs Merchant fulfilment?
- What is the order status breakdown?

Tools Used
- Power BI Desktop
- Power Query (Data Cleaning)
- DAX (Custom Measures)
- Microsoft Bing Maps

Dashboard Pages
Page 1 - Executive Dashboard:** KPI Cards, Monthly Trend, Category Sales, Fulfilment Donut, Order Status

Page 2 - Geographic Dashboard:** State-wise Map, Top States Bar Chart, City Analysis

Page 3 - Product Dashboard:** Category Revenue, Size Analysis, Treemap

Key DAX Measures
Total Revenue = SUM(dataset[Amount])
Total Orders = DISTINCTCOUNT('dataset'[Order ID])
Total Qty = SUM(dataset[Qty])
AOV = DIVIDE([Total Revenue],[Total Orders])

Key Insights
- Set and Kurta are top revenue categories
- Maharashtra is highest revenue state
- Merchant fulfilment = 69%, Amazon = 31%
- M and L sizes most popular
- Revenue peaked in April 2022

How to Use
1. Download the .pbix file
2. Open in Power BI Desktop
3. Use slicers to filter data
4. Click visuals to cross-filter
