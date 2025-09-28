# Sales-Performance-Analysis-Dashboard-using-Power-BI
An interactive Power BI dashboard designed to analyze sales performance, track KPIs (Revenue, Profit, Units Sold), identify top products &amp; sales reps, and visualize revenue trends across categories, subcategories, and time periods for data-driven decision-making.

## Project Objectives
Provide an interactive dashboard to monitor Total Revenue, Gross Profit, and Units Sold.
Identify top-performing products, categories, and subcategories driving sales.
Highlight top sales representatives contributing to company performance.
Analyze sales trends across years and months for better forecasting.
Support management in making data-driven decisions.

## Key Features of the Dashboard
 KPI Cards: Total Revenue, Gross Profit, Units Sold.
 Revenue breakdown by Category & SubCategory.
 Top 5 Sales Representatives performance.
 Product-wise and Year-wise revenue trends.
 Waterfall chart for increase/decrease analysis.
 Interactive slicers (Year, Month, Country).

├── # data                     
│   ├── dimensions/              # All dimension tables
│   │   ├── dim_products.csv
│   │   ├── dim_category.csv
│   │   ├── dim_subcategory.csv
│   │   ├── dim_salesrep.csv
│   │   └── dim_geography.csv
│   │
│   ├── facts/                   # All fact tables
│   │   ├── fact_sales2014.csv
│   │   ├── fact_sales2015.csv
│   │   ├── fact_sales2016csv
│   │   ├── fact_sales2017.csv
