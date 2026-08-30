# Superstore Sales Performance Dashboard | Power BI
An interactive 4-page Power BI dashboard analyzing sales, profit, discount, and order patterns of a retail Superstore dataset across categories, regions, time periods, and variance against targets.

 Overview
This dashboard breaks down retail performance from four different angles — product category, geography, time, and variance vs. goals — to help identify what's driving (and dragging) sales and profitability.

**Key Metrics Tracked:** Total Sales, Total Profit, Total Quantity, Total Discount, Total Units

 Dashboard Pages
 1. Category-Wise Analysis
- Sales and Profit breakdown by **Technology, Furniture, and Office Supplies**
- Month-wise Product Margin trend (Jan–Jun) across categories
- Interactive category slicer

 2. Region-Wise Analysis
- Drill-down **Regional Sales** hierarchy (Region → City)
- Discount % by Region (Central, East, West, South)
- Regional Profit distribution (donut chart)
- Sub-Category and Region filters

 3. Time-Wise Analysis
- Profit, Sales, Discount, and Quantity trends over time (Jan–Jun)
- Toggle views: Year / Month / Quarter / Days
- Monthly order volume distribution (pie chart)

 4. Variance Analysis
- Actual vs. Goal KPI cards (Sales, Profit, Discount, Quantity) with % variance
- Geographical sales map (US states)
- Unit Price by Category (waterfall/bridge chart)
- Profit & Quantity by Order Priority (Critical/High/Medium/Low/Not Specified)
- Region-wise monthly profit matrix table

 Key Insights

- **East region** leads in total sales (₹5.92L) and profit contribution, followed by West, Central, and South.
- **South region** shows negative profit in some months, indicating potential discount or cost inefficiencies.
- **Technology** carries the highest unit price contribution among categories.
- Profit shows strong seasonal growth from March to June, while March was a low point across most regions.
- Orders marked **"Not Specified"** priority contribute disproportionately high profit and quantity — worth flagging for data quality review.

Tools Used
- **Excel** - data cleaning
- - **Power BI Desktop** – data modeling, DAX measures, and visualization, Drill-through, slicers, and goal-tracking KPI visuals

 Dataset
Based on the standard **Superstore Sales dataset** (Category, Sub-Category, Region, Order Priority, Order Date, Sales, Profit, Discount, Quantity fields).

