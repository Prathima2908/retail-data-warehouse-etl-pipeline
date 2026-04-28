# Retail Data Warehouse ETL Pipeline

## 📌 Overview

This project demonstrates a complete end-to-end **Data Warehouse ETL pipeline** built using Python in Google Colab. It simulates real-world retail transactional data processing and transforms raw data into a structured, analytics-ready data warehouse.

The project covers data ingestion, transformation, staging, star schema modeling, and business KPI analysis, reflecting real industry data engineering workflows.

---

## 🏗️ Project Architecture

The pipeline follows a modern layered data architecture:

* **Raw Layer** → Raw transactional data generation
* **Staging Layer** → Cleaned and validated dataset
* **Data Warehouse Layer** → Star schema model

  * Fact Table (Sales transactions)
  * Dimension Tables (Customer, Product, Date, Region)

---

## 🔄 ETL Pipeline Process

### 1. Extract

* Synthetic retail dataset generated using Python
* Includes orders, customers, products, and transactions

### 2. Transform

* Data cleaning (duplicates, null handling)
* Data type standardization
* Feature engineering (Revenue calculation)
* Business rule validation

### 3. Load

* Structured data warehouse created:

  * Fact Sales Table
  * Customer Dimension Table
  * Product Dimension Table
  * Date Dimension Table

---

## 📊 Key Features

* End-to-end ETL pipeline implementation
* Star schema data warehouse design
* Fact and dimension modeling
* Business KPI analysis
* Revenue trend analysis
* Customer segmentation insights
* Data visualization dashboards

---

## 📈 Key Business Metrics

* Total Revenue
* Total Orders
* Unique Customers
* Product Category Performance
* Monthly Sales Trends
* Customer Segment Contribution

---

## 📊 Visualizations

* Revenue distribution analysis
* Category-wise revenue breakdown
* Monthly sales trends
* Correlation heatmaps
* Top-performing orders analysis
* Customer segmentation insights

---

## 🧰 Tech Stack

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Google Colab

---

## 📂 Project Structure

```text id="project_structure"
Retail_Data_Warehouse_ETL_Pipeline.ipynb
retail_raw_data.csv
staging_data.csv
fact_sales.csv
dim_customer.csv
dim_product.csv
dim_date.csv
```

---

## 🎯 Business Impact

This project demonstrates how raw transactional data can be transformed into a structured data warehouse that enables:

* Faster and scalable analytics
* Improved business decision-making
* Efficient KPI tracking and reporting
* Structured data modeling for enterprise systems
* Separation of raw and analytics-ready data layers

---

## 🚀 How to Run

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. Generate raw dataset and process ETL pipeline
4. View outputs and visualizations
5. Export final warehouse tables

---

## 📌 Key Learnings

* Data engineering ETL pipeline design
* Star schema modeling (Fact & Dimension tables)
* Data transformation and cleaning techniques
* Business KPI development
* End-to-end analytics pipeline design
* Data warehouse architecture fundamentals

---

## 👤 Author

Prathima Chinnabathini

---

## 🧠 Conclusion

This project demonstrates a complete end-to-end data engineering workflow, transforming raw retail transactional data into a structured and analytics-ready data warehouse. It highlights key data engineering principles including ETL design, star schema modeling, and KPI-driven analysis.

The pipeline reflects real-world industry practices used in modern data platforms to support scalable analytics and business decision-making.
