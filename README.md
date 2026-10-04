# 🏗️ SQL Data Warehouse Project

## 📌 Project Overview
This project demonstrates how to build a Data Warehouse using SQL and perform basic analytics on the data.

The main goal of this project is to:

Understand how raw data is converted into useful business data

Practice data warehousing concepts using SQL

Learn how analytics-ready tables are created for reporting

This project is created as a learning and portfolio project.

---

## 🧱 Data Warehouse Architecture

This project follows the **Medallion Architecture**:

### 🔹 Bronze Layer

* Stores raw data as received from source CSV files
* No transformations applied

### 🔹 Silver Layer

* Cleans and standardizes the raw data
* Handles missing values and formatting issues

### 🔹 Gold Layer

* Contains business-ready **fact and dimension tables**
* Designed using **star schema**
* Used for analytics, reports, and KPIs

---

## 📁 Repository Structure

```
sql_datawarehouse_project/
│
├── datasets/
│   ├── CUST_AZ12.csv
│   ├── LOC_A101.csv
│   ├── PX_CAT_G1V2.csv
│   ├── cust_info.csv
│   ├── prd_info.csv
│   └── sales_details.csv
│
├── docs/
│   ├── Data flow diagram.png
│   ├── silver.png
│   ├── star schema.png
│   └── data_catalog.md
│
├── scripts/
│   ├── bronze/
│   ├── silver/
│   └── gold/
│
├── tests/
│   ├── quality_checks_silver.sql
│   └── quality_checks_gold.sql
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## 📂 Folder Explanation (Beginner Friendly)

### 📁 datasets

Contains **raw source data** in CSV format related to:

* Customers
* Products
* Sales
* Locations

---

### 📁 docs

Contains **documentation and diagrams**:

* **Data Flow Diagram** – shows end-to-end data movement
* **Silver Layer Diagram** – explains cleaned data structure
* **Star Schema Diagram** – shows fact & dimension relationships
* **Data Catalog** – describes Gold layer tables and columns

---

### 📁 scripts

Contains **SQL scripts for each layer**:

* **bronze/** → raw data ingestion
* **silver/** → data cleaning and transformation
* **gold/** → analytical models and reporting views

---

### 📁 tests

Contains **data quality checks**:

* Validates record counts
* Checks null values
* Ensures data consistency in Silver and Gold layers

---

## 📊 Analytics & Reporting

The **Gold layer** supports:

* Exploratory Data Analysis (EDA)
* Customer and Product Reports
* Business KPIs
* Dashboard-ready datasets

---

## 🛠️ Tools & Skills Used

* SQL (T-SQL)
* Data Warehousing Concepts
* Medallion Architecture
* ETL Pipelines
* Data Modeling (Star Schema)
* Data Quality Checks
* Business Analytics

---

## 🎯 Key Learnings

* How to design a data warehouse from scratch
* How to structure data using Bronze, Silver, and Gold layers
* How to clean and transform data using SQL
* How to build analytics-ready models
* How to organize a real-world data project

---

## 👤 Author

**Lakshmi Mohan Krishna**
Data Engineer

🔗 [GitHub](https://github.com/almkrishna) | [LinkedIn](https://www.linkedin.com/in/almkrishna/)

---

## 📜 License

This project is licensed under the **MIT License**.

---

## ⭐ Final Note

This project is created for **learning, practice, and portfolio building**.
The focus is on **clear architecture, clean SQL, and real-world analytics use cases**.
