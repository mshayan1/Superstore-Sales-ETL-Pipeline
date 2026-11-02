
# 📊 Superstore Sales ETL Pipeline & Analytics Dashboard

## Project Overview

This project demonstrates an ETL pipeline built using Databricks, PySpark, SQL, and Delta Lake.

The pipeline processes Superstore sales data, performs data quality checks and transformations, stores processed data in Delta tables, and supports business analytics through SQL queries and a Databricks dashboard.

## 🛠️ Technologies Used

- Databricks
- PySpark
- SQL
- Delta Lake
- Unity Catalog
- Databricks Jobs
- Databricks Dashboards

## 🏗️ Project Architecture

```text
Superstore CSV Dataset
        |
        v
Unity Catalog Volume
        |
        v
Extract using PySpark
        |
        v
Data Cleaning & Transformation
        |
        v
Delta Table
        |
        v
Gold Analytics Table
        |
        v
SQL Analysis
        |
        v
Sales Analytics Dashboard
```

## 🔄 ETL Process

### 1. Extract

- Uploaded the Superstore CSV dataset to a Unity Catalog Volume.
- Loaded the dataset into a PySpark DataFrame.
- Inspected the dataset structure and columns.

### 2. Transform

- Checked missing values.
- Checked duplicate records.
- Converted Order Date and Ship Date into date types.
- Cleaned column names by replacing spaces with underscores.
- Prepared the dataset for analytics.

### 3. Load

- Stored the transformed dataset as a Delta table.
- Created a Gold analytics table for category-level sales analysis.
- Used SQL queries to analyze business performance.

## 📈 Analytics

The project includes analysis of:

- Total Sales
- Total Profit
- Total Orders
- Profit Margin
- Sales by Category
- Profit by Region
- Monthly Sales Trends
- Top 10 Products by Sales

## 📊 Dashboard

The Superstore Sales Analytics Dashboard provides a visual overview of business performance.

Dashboard features:

- KPI cards
- Sales trend visualization
- Category-level sales analysis
- Regional profit analysis
- Product performance analysis
- Interactive filters

## ⚙️ Automation

The ETL notebook was executed using Databricks Jobs.

The job successfully completed a manual run, demonstrating notebook execution through the Databricks workflow system.

## 📂 Project Files

```text
Superstore-Sales-ETL-Pipeline/
│
├── README.md
├── Ecommerce_ETL_Pipeline.ipynb
├── 02_Transform_Data.ipynb
└── images/
    └── sales_dashboard.png
```

## 🎯 Learning Outcomes

Through this project, I practiced:

- Building ETL pipelines with PySpark
- Working with Delta Lake tables
- Performing data quality checks
- Using Unity Catalog Volumes
- Writing analytical SQL queries
- Creating Gold analytics tables
- Executing notebooks through Databricks Jobs
- Developing business intelligence dashboards

## 👨‍💻 Author

**Muhammad Shayan**

Aspiring Data Engineer | PySpark | SQL | Databricks | Delta Lake
