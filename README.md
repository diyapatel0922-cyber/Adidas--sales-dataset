# Adidas--sales-dataset

<img width="1920" height="1020" alt="Screenshot 2025-11-07 135145" src="https://github.com/user-attachments/assets/51dba10f-30e8-4540-8e22-3c844ddcece1" />


Adidas Sales Dataset Dashboard Report

1. Data Model Setup
All sheets from Adidas Sales Data.xlsx were imported into Power BI.
Relationships created:
•	Sales : Products via ProductID
•	Sales : Channels via ChannelID
•	Sales : Stores via StoreID
•	Sales : Customers via CustomerID
The model diagram shows a star schema connecting fact and dimension tables.

2. Data Cleaning
Using Power Query Editor:
•	Replaced blank Regions with “Unknown”.
•	Removed duplicate rows from the Sales table.
•	Ensured Date columns are properly formatted.
•	Calculated new columns such as Gross Margin = Revenue – Cost and Discount %.

3. Multivariate Analysis
•	Funnel Chart: Show total orders → delivered → returned sales amounts.
•	Category-based Analysis: Analyze sales performance based on product category, gender, and region.
•	Customer Demographics: Compare revenue based on age, gender, and loyalty tier.
•	Sales Trend Analysis: Time-based line chart to show sales growth and seasonal variation.



4. Dashboard Layout
A single dashboard page designed with clear visuals:
KPI Cards: Total Sales, Total Units Sold, Total Revenue, Average Discount, Gross Margin %.
Visuals included:
•	Map: Region-wise total sales.
•	Bar Chart: Product category-wise sales.
•	Donut Chart: Channel-wise sales distribution.
•	Line Chart: Monthly revenue trend.

5. Slicer Interaction
Added interactive Slicers for Product Category, Region, and Channel:
•	Category: Products (Category)
•	Region: Stores (Region)
•	Channel: Channels (Channel Name)

