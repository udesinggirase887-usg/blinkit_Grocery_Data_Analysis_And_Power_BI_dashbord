# Blinkit Grocery Sales Performance Analysis And Power BI dashbord

# Short Project Description
An interactive Power BI dashboard designed to monitor and analyze Blinkit’s sales performance, customer satisfaction, and inventory distribution. This project transforms raw retail data into actionable insights to optimize business operations and outlet performance.

#Project Overview
The objective of this dashboard is to provide a holistic view of Blinkit’s sales ecosystem. It solves the problem of fragmented data by centralizing key metrics such as total revenue, customer ratings, and item visibility. By analyzing variables like outlet size and location, the dashboard provides strategic insights into which factors most significantly drive grocery sales and customer retention.

#Dataset Description
> The analysis is performed on the BlinkIT Grocery Data dataset, which contains approximately 8,500 records.

> Key Variables: * Item Fat Content: Categorical (Low Fat, Regular, and variations like 'LF', 'low fat').

> Item Type: 16 categories including Fruits, Vegetables, Snack Foods, and Household items.

> Outlet Establishment Year: Longitudinal data from 2010 to 2022.

> Outlet Size: Categorized as Small, Medium, and High.

> Outlet Location Type: Tier 1, Tier 2, and Tier 3 cities.

> Metrics: Sales (Decimal), Rating (Integer 1-5), and Item Visibility.

# Key Performance Indicators (KPIs)
The dashboard tracks the following high-level metrics (calculated using DAX):

> Total Sales: The overall revenue generated ($1.20M).

> Average Sales: The average revenue per transaction ($141).

> Number of Items: Total count of unique products sold (8,523).

> Average Rating: The collective customer satisfaction score (3.9).

# Dashboard Visualizations
> Donut Charts: Comparison of sales across Item Fat Content and Outlet Size.

> Stacked Bar Charts: Detailed breakdown of Sales by Item Type to identify top-performing categories.

> Line Chart: Visualizing the Outlet Establishment Trend over the years.

> Funnel & Matrix Charts: Analyzing Sales by Outlet Location (Tier) and Outlet Type performance.

> Interactive Slicers: Filtering capabilities for Outlet Location Type, Outlet Size, and Item Type.

# Tools and Technologies Used
Power BI Desktop: Core tool for data modeling and dashboard creation.

DAX (Data Analysis Expressions): Used for advanced measures like Total Sales and Avg Sales.

Power Query: Employed for data cleaning, specifically for standardizing "Fat Content" labels and handling missing values in "Outlet Size."

Excel / CSV: Source data format.

# Key Insights
> Growth Trend: There was a significant peak in outlet establishments in 2018, contributing to the highest recorded sales growth in that period.

> Consumer Preference: Low Fat products contribute to roughly 64% of total sales compared to Regular fat items.

> Top Performers: Fruits & Vegetables and Snack Foods are the leading categories in terms of revenue.

>Location Strategy: Tier 3 locations generate the maximum revenue, despite having a mix of outlet types, suggesting higher volume or better market penetration.

# Future Improvements
> Sentiment Analysis: Integrate customer review text to deep-dive into the "Rating" metric.

> Price Optimization: Analyze the correlation between Item MRP and sales volume to suggest optimal pricing.

> Real-time Integration: Connecting the dashboard to a live SQL database or web API for real-time sales tracking.

