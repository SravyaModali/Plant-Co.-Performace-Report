Plant Co. Performance Dashboard (Power BI)
📊 Project Overview

This project presents a dynamic Power BI dashboard designed to analyze Plant Company’s 2023 performance, focusing on Year-to-Date (YTD) vs Previous Year-to-Date (PYTD) comparisons.

The report enables stakeholders to:

Monitor overall business performance
Identify key drivers of growth and decline
Analyze trends across time, geography, and product categories
Drill down into deeper insights for decision-making

🎯 Objective

The primary goal of this dashboard is to provide a condensed, interactive performance view that supports:

Executive-level decision making
Root cause analysis of performance changes
Identification of high and low performing regions/products

🧩 Data Model

The report follows a star schema design for optimized performance and scalability:

Fact Table
Fact_Sales: Sales, Quantity, Price, COGS, Date, Product, Account
Dimension Tables
Dim_Date: Date intelligence and time-based calculations
Dim_Account: Country, Account details, geographic attributes
Dim_Product: Product hierarchy (Family, Group, Type, Size)

⚙️ Key Features

🔄 Dynamic Measure Selection
Implemented using SWITCH() in DAX
Allows users to toggle between:
Quantity
Sales
Gross Profit

📅 Time Intelligence
YTD vs PYTD comparisons
Monthly contribution analysis
Variance calculations

📉 Visualizations

🟦 KPI Cards
YTD, PYTD, Variance, and Gross Profit %
Provides quick high-level performance summary

🌍 Treemap (Bottom Performers)
Highlights countries contributing negatively to growth
Helps identify regions requiring attention

📊 Waterfall Chart
Shows monthly contribution to YTD variance
Identifies key periods of growth and decline

📈 Line + Clustered Column Chart
Compares YTD vs PYTD across countries
Supports drill-through for deeper country-level analysis

🍩 Donut Chart
Displays sales contribution by product type
Helps understand product mix

🔍 Interactivity
Drill Down
Enabled in waterfall chart for deeper breakdown
Drill Through (Country-Level)
Allows detailed analysis of individual country performance
Slicers
Year selection
Metric selection (Quantity, Sales, Profit)

📌 Key Insights

Overall performance shows positive growth in YTD vs PYTD, but not uniformly across all regions
Certain countries (e.g., China, France) contribute significantly to decline
Performance is volatile across months, with strong mid-year gains and late-year dips
Outdoor products contribute the highest share, indicating a key revenue driver

🛠️ Tools & Technologies

Power BI
DAX (SWITCH, Time Intelligence, Aggregations)
Data Modeling (Star Schema)
Excel (Data preparation)

🚀 How to Use

Open the .pbix file in Power BI Desktop
Use the slicers to switch between metrics and time periods
Hover over visuals for additional insights
Use drill-down and drill-through features for deeper analysis

📈 Future Enhancements

Add forecasting and trend prediction
Implement decomposition tree for root cause analysis
Include alerts for sudden performance drops
Integrate real-time or streaming data
