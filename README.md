☕ Coffee Shop Sales Analysis – Alteryx Workflow

📌 Project Overview

This project demonstrates how Alteryx can be used to transform raw sales data into actionable business insights.
Using a coffee shop sales dataset, I built an end-to-end workflow to analyze performance across products, categories, locations, and time trends.

The workflow automates the ETL process (Extract, Transform, Load), applies data cleaning and transformation, generates new calculated fields, and produces structured reports for business decision-making.

🎯 Objectives

The project was designed around 4 key business use cases:

1️⃣ Category Performance – Compare revenue across product categories (Beverages, Bakery, etc.).

2️⃣ Peak Sales Days – Identify the highest revenue-generating dates and seasonal patterns.

3️⃣ Location-Wise Sales – Evaluate which store locations contributed most to total sales.

4️⃣ Top-Selling Products – Determine which products drive the highest revenue.

🛠 Workflow Steps

Input Data
Imported the dataset coffee_shop_sales.csv containing sales transactions.

Data Preparation
Cleaned and formatted data (data types, missing values, consistency checks).

New Field Creation
Added a calculated field:
Total Sales = Units Sold * Unit Price

Branching the Analysis
By Product → Identify top-selling products.
By Location → Compare city-level sales.
By Date → Detect peak sales days.
By Category → Analyze category-level performance.

Aggregation & Ranking
Summarized totals for each branch.
Sorted results in descending order to highlight top contributors.

📊 Key Insights

Category Performance: Beverages generated the highest revenue ($1,137,002.5), followed by Bakery ($766,050.5).

Peak Sales Days: August 4, 2024, saw $7,363 in sales, with strong spikes during Nov–Dec holidays.

Location Sales: New York ($482K) led, followed closely by San Francisco ($478K), Los Angeles ($471K), and Chicago ($470K).

Top Products: Latte ($451K), Cold Brew ($392K), and Croissant ($312K) were the best performers.


🚀 Tools & Technologies

Alteryx Designer → Workflow automation & analysis

CSV Reports → Exported outputs


💡 Business Value

This project highlights how data analytics workflows can help businesses:

Identify revenue-driving products and categories

Detect demand peaks for better staffing & inventory planning

Compare store performance across locations

Make data-driven decisions for marketing and operations
