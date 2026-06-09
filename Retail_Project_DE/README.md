# 🚀 Retail Analytics Data Engineering Project

## Overview

Built an end-to-end Azure Data Engineering pipeline using Azure Data Factory, Azure Data Lake Storage Gen2, Azure Databricks, Delta Lake, Unity Catalog, and Power BI.

The project follows the Medallion Architecture (Bronze → Silver → Gold) to ingest, transform, and analyze retail sales data.

---

## Architecture

```text
Retail CSV Dataset
        ↓
Azure Data Factory
        ↓
Azure Data Lake Storage Gen2
        ↓
Bronze Layer (Raw Data)
        ↓
Silver Layer (Cleaned Data)
        ↓
Gold Layer (Business Aggregations)
        ↓
Power BI Dashboard
```

---

## Tech Stack

- Azure Data Factory
- Azure Data Lake Storage Gen2
- Azure Databricks
- Apache Spark
- Delta Lake
- Unity Catalog
- SQL
- Power BI

---

## Key Features

✅ Automated Data Ingestion using Azure Data Factory

✅ Bronze, Silver and Gold Medallion Architecture

✅ Data Cleaning and Transformation using PySpark

✅ Revenue and Product Analytics using Spark SQL

✅ Interactive Power BI Dashboard

---

## Data Pipeline

### Bronze Layer
- Raw retail transaction data
- Delta table creation

### Silver Layer
- Null handling
- Data cleansing
- Revenue calculation

### Gold Layer
- Monthly Revenue Analysis
- Top Products Analysis
- Country-wise Revenue Analysis

---

## Dashboard KPIs

- Total Revenue: $8.34M
- Total Orders: 15,148
- Countries Served: 36

---

## Project Structure

```text
├── notebooks
│   ├── 01_Checking.ipynb
│   ├── 02_bronze.ipynb
│   ├── 03_silver.ipynb
│   ├── 04_gold_aggregations.ipynb
│   └── 05_bussiness_Queries.ipynb
│
├── dashboard
│   └── Retail-project-dashboard.pdf
│
├── screenshots
│   ├── adf_pipeline.png
│   ├── bronze_layer.png
│   ├── silver_layer.png
│   ├── gold_layer.png
│   └── powerbi_dashboard.png
│
└── README.md
```

---

## Dashboard Preview

![ADF Pipeline](screenshots/adf_pipeline.png)

![Power BI Dashboard](screenshots/powerbi_dashboard.png)

---

## Skills Demonstrated

- Azure Data Factory
- Azure Databricks
- Azure Data Lake Storage Gen2
- Delta Lake
- PySpark
- Spark SQL
- ETL Pipeline Development
- Medallion Architecture
- Power BI

---

## Author

**Ram**

