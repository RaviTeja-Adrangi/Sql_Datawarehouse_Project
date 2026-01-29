
📊 Data Warehouse and Analytics Project

Welcome to the Data Warehouse and Analytics Project repository 🚀
This project showcases an end-to-end data warehousing and analytics solution — from building a modern data warehouse to delivering meaningful analytical insights.


🚀 Project Overview

🏗️ Building the Data Warehouse (Data Engineering)

🎯 Objective
Design and implement a modern data warehouse using Microsoft SQL Server to consolidate sales data and enable efficient analytical reporting and data-driven decision-making.

## 📋 Project Requirements

### 🔹 Data Sources
- Ingest data from two source systems (**ERP** and **CRM**) provided in CSV format.

### 🔹 Data Quality
- Perform data cleansing and resolve data quality issues before loading data into the data warehouse.

### 🔹 Data Integration
- Integrate data from multiple sources into a unified, user-friendly data model optimized for analytical queries.

### 🔹 Scope
- Focus on **current/latest data only**; historical data tracking is out of scope.

### 🔹 Documentation
- Provide clear and structured documentation of the data model to support both business users and analytics teams.

TL;DR

This project focuses on transforming raw CSV data into meaningful business insights using the Medallion Architecture.

Bronze layer: Raw CSV files are ingested as-is into tables by creating the required databases, schemas, and tables.

Silver layer: Data is loaded from Bronze using ELT, cleaned, transformed, and standardized. All transformations are organized into stored procedures for easy execution and reusability.

Gold layer: Business-ready views are created to expose curated data for reporting and analytics.

👉 The end goal is to deliver clean, reliable, and insight-ready data that directly supports business decision-making.

