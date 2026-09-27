# Databricks Data Engineering & BI Project

## 📌 Project Overview

This project demonstrates an end-to-end **Data Engineering and Analytics pipeline using Databricks**, following the **Medallion Architecture (Bronze → Silver → Gold)**.

The objective is to ingest raw **CSV and JSON files from an on-premises data source**, perform data transformation and cleansing using **PySpark and Spark SQL**, store the processed data in **Delta Lake**, and build an interactive **Databricks Dashboard** for business-level analysis.

## 🏗️ Architecture

**On-Premises Data → Bronze → Silver → Gold → Databricks Dashboard**

### 🥉 Bronze Layer – Raw Data

* Imported **CSV and JSON files** from on-premises data sources into the Databricks environment.
* Stored the raw and unprocessed data in the **Bronze Layer**.
* Preserved the original source structure for **data lineage, traceability, and reprocessing**.
* Used **Delta Lake** for reliable and scalable data storage.

### 🥈 Silver Layer – Data Transformation

Data transformation was performed using a **Databricks Notebook (`DB_notebook`)** with **PySpark and Spark SQL**.

Key processing activities included:

* Data cleansing and standardization
* Data type conversion
* Handling null and inconsistent values
* Column transformation and derivation
* Data validation and quality checks
* Filtering and joining datasets
* Applying business transformation logic

The cleansed and transformed datasets were stored as **Delta Tables** in the Silver Layer.

### 🥇 Gold Layer – Business Aggregation

The Gold Layer contains **business-ready and aggregated datasets** designed for analytics and reporting.

Key activities included:

* Business-level aggregations
* KPI calculation
* Group-by and aggregation operations
* Metric derivation
* Preparing optimized datasets for BI consumption

The final datasets were stored in **Delta Lake** as Gold-layer Delta Tables.

## 📊 Databricks Dashboard

An interactive **Databricks Dashboard** was developed using the Gold-layer datasets.

The dashboard includes:

* Interactive filters
* KPI visualizations
* Bar and line charts
* Category-wise analysis
* Trend analysis
* Business performance metrics
* Dynamic data exploration

Users can apply filters and interact with visualizations to analyze the underlying business data.

## 🛠️ Technologies Used

**Databricks | Delta Lake | PySpark | Spark SQL | SQL | Python | Medallion Architecture | Data Engineering | ETL/ELT | Data Transformation | Data Quality | Data Aggregation | Databricks SQL | Databricks Dashboard**
