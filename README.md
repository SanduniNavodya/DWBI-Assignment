# DWBI-Assignment
SLIIT Y3 S2 DWBI Assignment

## 📘 Hospital Data Warehousing & Business Intelligence

This repository contains assignment work submitted for the **IT3021 – Data Warehousing and Business Intelligence** course at Sri Lanka Institute of Information Technology. The project covers both data warehouse design and business intelligence implementation for a hospital system.

---

## 📂 Assignment 01 – Data Warehouse Design
### 🔹 Features:
- Galaxy Schema-based Data Warehouse
- Source data from CSV files, text documents, and `.bak` database backup
- Full ETL pipeline with SQL Server Integration Services (SSIS)
- Dimension and Fact tables like:
  - `DimPatient`, `DimEmployee`, `DimRoom`, `DimMedication`
  - `FactMedication`, `FactRecord`, `DimDate`, etc.
- Custom SQL script for generating a detailed `DimDate` dimension
- Comprehensive data profiling and staging process

📄 Report: [`IT22589590_Assignment_01_Report.pdf`](./IT22589590_Assignment_01_Report.pdf)

---

## 📊 Assignment 02 – OLAP & Business Intelligence

### 🔹 Features:
- OLAP Cube implementation with SQL Server Analysis Services (SSAS)
- Dimensions with hierarchies (e.g., Date: Year > Quarter > Month > Day)
- KPIs:
  - Total Medication Cost
  - Treatment Duration
- OLAP operations demonstrated:
  - Roll-up, Drill-down, Slice, Dice, Pivot
- Power BI Dashboards:
  - Medication usage matrix
  - Drill-down treatment dashboard
  - Interactive reports with slicers and drill-throughs

📄 Report: [`IT22589590_Assignment_02_Report.pdf`](./IT22589590_Assignment_02_Report.pdf)

---

## 🛠 Tools & Technologies Used

- Microsoft SQL Server
- SSIS (SQL Server Integration Services)
- SSAS (SQL Server Analysis Services)
- Power BI
- Excel for OLAP operations
- Visual Studio SSDT

