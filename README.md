📊 Sales Insights Dashboard
📌 Project Overview

This project demonstrates the end-to-end process of transforming raw sales data into actionable business insights using Python and Power BI. The workflow simulates a real-world analytics pipeline — from data cleaning and exploratory analysis in Python, to building an interactive Power BI dashboard for executives.

🛠️ Tools & Technologies

Excel – initial dataset format
Python – data cleaning & exploratory analysis
Libraries: numpy, pandas, matplotlib
Power BI – interactive dashboard & KPIs

🎯 Objectives

Prepare and clean raw sales data for analysis.
Perform EDA to identify key patterns and anomalies.
Build a Power BI dashboard to track revenue, profit, and product performance.
Deliver business insights to support data-driven decision-making.

📂 Workflow

Business Understanding
Focus on KPIs: revenue, profit, sales by channel, top/bottom products, regional performance.

Data Cleaning (Python)
Removed duplicates, handled missing values, standardized formats.
Derived calculated fields like profit and profit_margin_pct.

Exploratory Data Analysis (Python)
Revenue and profit trends by month and year.
Product-level and region-level performance.
Correlation between pricing, revenue, and costs.

Power BI Dashboard
KPIs: Total Revenue, Profit, Product Count.
Charts:
Line chart for revenue trend
Pie chart for channel contribution
Bar chart for top products
Filters for product, month, and channel.

📑 Data Dictionary
| Column Name       | Description                                             | Example Value |
| ----------------- | ------------------------------------------------------- | ------------- |
| order_number      | Unique identifier for each order                        | 1001          |
| order_date        | Date when the order was placed                          | 2021-05-12    |
| channel           | Sales channel (e.g., Wholesale, Distributor)            | Wholesale     |
| order_quantity    | Quantity of units ordered                               | 6             |
| unit_price        | Price per unit                                          | 2499.1        |
| revenue           | Total revenue (order_quantity × unit_price)             | 14994.6       |
| total_unit_cost   | Total cost of units sold                                | 1824.34       |
| profit            | Revenue – total_unit_cost                               | 13170.26      |
| profit_margin_pct | Profit as % of revenue                                  | 87.8%         |
| customer_name     | Name of the customer                                    | John Doe      |
| product_name      | Product sold                                            | Laptop        |
| county            | Customer’s county                                       | Los Angeles   |
| state             | Customer’s state                                        | California    |
| state_code        | Abbreviation of state                                   | CA            |
| region            | Geographic region                                       | West          |
| latitude          | Geographic latitude                                     | 34.05         |
| longitude         | Geographic longitude                                    | -118.24       |
| budget_2024       | Budgeted revenue for 2024 (for comparison with actuals) | 20000         |
| month_name        | Name of the month                                       | January       |
| month_num         | Numeric representation of the month                     | 1             |

📁 Repository Structure
Sales-Insights-Dashboard  
├── notebooks/        # Python scripts / Jupyter notebooks  
├── dashboard/        # Power BI .pbix file  
├── README.md         # Project documentation  

🔮 Future Improvements

Forecast sales using time-series models.
Automate ETL pipelines for live dashboard refresh.
Add customer segmentation using clustering.

👩‍💻 Author

Created by Sakshi Padhye – Data Analyst / BI Enthusiast
