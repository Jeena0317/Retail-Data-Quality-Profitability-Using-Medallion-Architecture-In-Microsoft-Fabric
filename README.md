Retail Data Engineering Pipeline using Medallion Architecture (Microsoft Fabric)
📌 Project Overview

This project demonstrates an end-to-end data engineering pipeline using Microsoft Fabric and PySpark, implementing the Medallion Architecture (Bronze, Silver, Gold layers).

The pipeline processes raw retail data, performs data cleaning and transformation, and generates business-ready insights such as revenue, return rate, and profitability.

🏗️ Architecture
Bronze Layer
Raw data ingestion from source (CSV/JSON/API) without transformations
Silver Layer
Data cleaning and transformation:
Standardized column names
Handled missing values
Converted data types
Cleaned currency, dates, and text fields
Removed duplicates
Gold Layer
Business-level aggregations:
Total Orders
Unique Customers
Total Revenue
Return Rate (%)
Average Order Value
Profitability Metrics
⚙️ Technologies Used
Microsoft Fabric
PySpark
Delta Lake
SQL
Data Modeling
📂 Datasets Used
Orders Data (CSV/JSON)
Inventory Data
Returns Data
🔄 Pipeline Flow
Ingest raw data into Bronze layer
Clean and transform data into Silver layer
Join datasets and calculate KPIs in Gold layer
Store results as Delta tables
📊 Key Features
Implemented Medallion Architecture
Built scalable ETL pipeline using PySpark
Handled inconsistent data formats (dates, currency, text)
Performed data validation and deduplication
Generated business KPIs for analytics
📈 Sample KPIs
Total Revenue
Total Orders
Return Rate (%)
Average Order Value
Net Profit
🚀 How to Run
Upload datasets to Microsoft Fabric Lakehouse
Run Bronze layer ingestion notebook
Run Silver layer cleaning notebooks
Run Gold layer aggregation notebook
Query final tables for insights
🎯 Project Outcome
Built a complete data pipeline from raw data to insights
Improved data quality and consistency
Enabled business reporting using structured data
📌 Future Improvements
Add real-time data ingestion
Implement SCD Type 2
Build Power BI dashboard
Optimize pipeline for large-scale data
👤 Author

Jeena Paul
📧 jeenapaul0317@gmail.com

🔗 GitHub: https://github.com/Jeena0317
