# E-Commerce Data Lakehouse (Engineering + Analytics)

Welcome to the **E-Commerce Data Lakehouse (Engineering + Analytics)** repository! 🚀  
This project designed as a portfolio demonstrates a comprehensive data engineering and analytics solution.

---
## 🏗️ Architecture

This project follows the **Medallion Architecture**:

### 🥉 Bronze Layer
- Raw data ingestion  
- Schema inference and storage as Delta tables  

### 🥈 Silver Layer
- Data cleaning and standardization  
- Type casting and validation  

### 🥇 Gold Layer
- Dimensional Data Model (Business Transformation)
- Ready for BI and analysis 

---

## 🛠️ Technologies Used

- Databricks  
- Apache Spark  
- PySpark  
- Spark SQL  
- Delta Lake  
- Unity Catalog  

---

## 📖 Project Overview

This project involves:

1. **Data Architecture**: Designing a Data Lakehouse Using Medallion Architecture **Bronze**, **Silver**, and **Gold** layers.
2. **ETL Pipelines**: Extracting, transforming, and loading data from source systems into the lakehouse.
3. **Data Analytics and Reporting**: Creating SQL-based reports and dashboards for actionable insights.

---

## 🚀 Project Requirements

### Building the Data Lakehouse (Data Engineering)

#### Objective
Develop a data lakehouse using Databricks to ingest, cleanse, transform, and structure sales data into analytical-ready datasets, enabling analytical reporting and data-driven decision-making.

#### Specifications
- **Data Sources**: Import sales data from a single source system provided in CSV format.
- **Data Quality**: Cleanse, transform, and resolve data quality issues before analysis.
- **Integration**: Integrate and structure data to support analytical queries and reporting.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.

---

### BI: Analytics & Reporting (Data Analysis)

#### Objective
Develop SQL-based analytics to deliver detailed insights into:
- **Daily Revenue**
- **Top Performing Product**
- **Best Selling SKU**

These insights empower stakeholders with key business metrics, enabling strategic decision-making.

## 📂 Repository Structure
```
data-lakehouse-project/
│
├── datasets/                           # Raw datasets used for the project
│
├── docs/                               # Project documentation and architecture details
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│
├── code/                               # python/pyspark scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
└── LICENSE                             # License information for the repository
```
---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE). You are free to use, modify, and share this project with proper attribution.

## 🌟 About Me

Hi there! I'm **Amirul Zikry**, a Digital Marketing professional with a strong interest in **Data Engineering and Data Analytics**. With a background in Computer Science and hands-on experience in data-driven marketing, I’m currently seeking an opportunity to transition into the data field and build my career as a **Data Engineer / Data Analyst**.

Let's stay in touch! Feel free to connect with me on the following platform:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amirul-zikry/)
