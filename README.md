# Data Warehouse and Analytics Project

A comprehensive data warehousing solution showcasing end-to-end implementation from data architecture design to optimized analytical models. This project demonstrates professional-grade data engineering capabilities.

---
## 🏗️ Data Architecture

This project implements a modern Medallion Architecture with **Bronze**, **Silver**, and **Gold** layers:
![Data Architecture](docs/data_architecture.png)

1. **Bronze Layer**: Raw data ingestion from source systems (CSV files) into SQL Server Database.
2. **Silver Layer**: Data cleansing, standardization, and normalization for analysis-ready datasets.
3. **Gold Layer**: Business-ready data modeled in star schema optimized for reporting and analytics.

---
## 📖 Project Summary

**Key Accomplishments:**

- Designed and implemented a scalable data warehouse using Medallion Architecture
- Built robust ETL pipelines for data extraction, transformation, and loading
- Developed optimized fact and dimension tables for analytical queries
- Created comprehensive technical documentation for the data warehouse
- Managed project execution using structured task tracking

**Technical Skills Demonstrated:**
- Data Architecture & Design
- SQL Development & Optimization
- ETL Pipeline Development
- Dimensional Data Modeling
- Data Quality Management
- Project Management & Documentation

---

## 🛠️ Technologies Used

- **SQL Server (Linux) via Docker** - Database platform
- **Azure Data Studio** - Database development and management
- **Notion** - Project planning and task tracking
- **Git & GitHub** - Version control
- **Draw.IO** - Architecture and data model visualization

---

## 🚀 Project Scope

### Data Warehouse Implementation

**Objective:** Consolidated sales data from multiple source systems into a unified analytical platform.

**Key Features:**
- Integrated data from two source systems (ERP and CRM)
- Implemented comprehensive data quality controls
- Designed user-friendly dimensional model for business analytics
- Optimized for analytical query performance

For detailed requirements, see [docs/requirements.md](docs/requirements.md).

---

## 📂 Project Structure
```
data-warehouse-project/
│
├── datasets/                           # Source data files (CRM and ERP)
│
├── docs/                               # Technical documentation
│   ├── data_layers.pdf                 # ETL design and implementation patterns
│   ├── data_architecture.png           # Architecture diagram
│   ├── data_catalog.md                 # Data dictionary and metadata
│   ├── data_flow.png                   # Data flow documentation
│   ├── data_integration.png            # Data source mapping diagram
│   ├── data_models.png                 # Star schema models
│   ├── naming-conventions.md           # Naming standards
│
├── scripts/                            # SQL implementation scripts
│   ├── bronze/                         # Raw data ingestion layer
│   ├── silver/                         # Data transformation layer
│   ├── gold/                           # Analytical model layer
│
├── tests/                              # Quality assurance scripts
│
├── .gitignore                          # Git ignore rules
├── LICENSE                             # License information
├── README.md                           # Project documentation
```
---

## 📊 Key Deliverables

✅ Fully functional data warehouse with medallion architecture  
✅ Automated ETL pipelines for data processing  
✅ Optimized star schema for analytical queries  
✅ Comprehensive technical documentation  
✅ Analysis-ready dimensional model  
✅ Structured project tracking and task management

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).
