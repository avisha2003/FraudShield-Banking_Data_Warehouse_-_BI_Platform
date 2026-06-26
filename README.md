# Bank Fraud Detection Data Warehouse & BI Platform

## Project Overview

This project demonstrates the design and implementation of an end-to-end Data Warehouse and Business Intelligence solution for banking fraud analysis.

The solution integrates multiple heterogeneous data sources, performs ETL processing using SQL Server Integration Services (SSIS), stores analytical data in a Star Schema Data Warehouse, enables multidimensional analysis through SQL Server Analysis Services (SSAS) Cubes, and provides OLAP and visualization capabilities using Excel and Power BI.

---

## Technologies Used

* Microsoft SQL Server
* SQL Server Integration Services (SSIS)
* SQL Server Analysis Services (SSAS)
* SQL Server Data Tools (SSDT)
* Microsoft Excel
* Power BI Desktop
* Power BI Service

---

## Data Sources

* Excel Transaction Dataset
* CSV Merchant Dataset
* SQL Server Customer Dataset

---

## Architecture

Source Systems
→ Staging Area
→ SSIS ETL
→ Data Warehouse
→ SSAS Cube
→ Excel OLAP Analysis
→ Power BI Dashboards

---

## Data Warehouse Design

### Fact Table

Fact_Transactions

Measures:

* Transaction Amount
* Account Balance
* Is Fraud

### Dimension Tables

* Dim_Customer
* Dim_Merchant
* Dim_Date

---

## Data Warehouse Concepts Implemented

* Star Schema
* ETL Process
* Staging Area
* Surrogate Keys
* Lookup Transformations
* Slowly Changing Dimension (Type 2)
* Accumulating Fact Table

---

## SSAS Cube

Implemented:

* Measures
* Dimensions
* Date Hierarchy (Year → Quarter → Month)

---

## OLAP Operations

Implemented using Excel Pivot Tables:

* Roll-up
* Drill-down
* Slice
* Dice
* Pivot

---

## Power BI Reports

### Report 1

Matrix Visual

### Report 2

Cascading Slicers Dashboard

### Report 3

Drill-Down Report

### Report 4

Drill-Through Report

---

## Author

Kavindu Lahiru
Data Science Undergraduate

