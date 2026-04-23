# Retail Data Engineering Pipeline using Medallion Architecture (Microsoft Fabric)

---

## 📌 Project Overview

This project demonstrates an end-to-end data engineering pipeline using **Microsoft Fabric** and **PySpark**.

It implements the **Medallion Architecture (Bronze, Silver, Gold layers)** to process raw retail data and generate business insights.

---

## 🏗️ Architecture

### 🔹 Bronze Layer
- Raw data ingestion from source (CSV / JSON / API)  
- No transformations applied  

### 🔹 Silver Layer
- Data cleaning and transformation  
- Standardized column names  
- Handled missing values  
- Converted data types  
- Cleaned currency, dates, and text fields  
- Removed duplicates  

### 🔹 Gold Layer
- Business-level aggregations  
- Generated KPIs for reporting and analytics  

---

## ⚙️ Technologies Used

- Microsoft Fabric  
- PySpark  
- Delta Lake  
- SQL  

---

## 📂 Datasets Used

- Orders Data  
- Inventory Data  
- Returns Data  

---

## 🔄 Pipeline Flow

1. Ingest raw data into Bronze layer  
2. Clean and transform data into Silver layer  
3. Join datasets and calculate KPIs in Gold layer  
4. Store results as Delta tables  

---

## 📊 Key Features

- Implemented Medallion Architecture  
- Built scalable ETL pipeline using PySpark  
- Handled inconsistent data formats (dates, currency, text)  
- Performed data cleaning and deduplication  
- Generated business KPIs  

---

## 📈 Sample KPIs

- Total Revenue  
- Total Orders  
- Return Rate (%)  
- Average Order Value  
- Net Profit  

---

## 🚀 How to Run

1. Upload datasets to Fabric Lakehouse  
2. Run Bronze layer notebook  
3. Run Silver layer notebook  
4. Run Gold layer notebook  
5. Query the final tables  

---

## 🎯 Project Outcome

- Built end-to-end data pipeline  
- Improved data quality and consistency  
- Enabled business insights using structured data  

---

## 📌 Future Improvements

- Add real-time data ingestion  
- Implement SCD Type 2  
- Build Power BI dashboard  
- Optimize pipeline performance  

---

## 👤 Author

**Jeena Paul**  

📧 jeenapaul0317@gmail.com  

🔗 GitHub: https://github.com/Jeena0317  
