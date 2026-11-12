# E-Commerce & Logistics Analytics Pipeline

## 📌 Project Overview
This project simulates a production-grade end-to-end data engineering and analytics pipeline for an e-commerce business. Using real-world e-commerce transaction and logistics data, the pipeline automates data ingestion, stores raw and transformed data in a cloud data warehouse, and delivers actionable business intelligence dashboards.

### Business Objectives
* **Sales Performance:** Track revenue trends, average order value (AOV), and top-performing product categories.
* **Supply Chain & Logistics:** Identify delivery bottlenecks, measure average shipping times, and analyze carrier delays across geographical regions.

## 1. Architecture
`Raw Data (CSV/API)` ➔ `Orchestration (Airflow / Docker)` ➔ `Cloud Data Warehouse (Snowflake)` ➔ `Data Modeling (SQL Star Schema)` ➔ `BI Visualization (Power BI)`

## 2. Tech Stack
* **Cloud Data Warehouse:** Snowflake
* **Orchestration & Containerization:** Apache Airflow, Docker
* **Data Transformation & Modeling:** SQL
* **Business Intelligence:** Power BI Desktop
* **Version Control & CI/CD:** Git, GitHub, GitHub Actions

## 3. Repository Structure
* `/data` – Scripts and instructions for data ingestion.
* `/sql` – DDL scripts, staging queries, and dimensional modeling (Fact/Dimension tables).
* `/airflow` – DAGs and Docker configurations for pipeline automation.
* `/dashboards` – Power BI report files and dashboard previews.

## 4. Project Roadmap
- [x] **Phase 1:** Environment setup, GitHub repository structure, and Snowflake initialization.
- [ ] **Phase 2:** Data ingestion and staging in Snowflake.
- [ ] **Phase 3:** Data cleaning and Star Schema dimensional modeling in SQL.
- [ ] **Phase 4:** Interactive Power BI dashboard development.
- [ ] **Phase 5:** Pipeline automation with Airflow/Docker and CI/CD via GitHub Actions.
