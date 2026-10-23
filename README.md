# databricks-ecommerce-data-engineering
End-to-end e-commerce data engineering project using Databricks, PySpark, Delta Lake, SQL, Genie AI, and dashboards.
# End-to-End E-Commerce Data Engineering Project

## 1. Project Overview

This project implements an end-to-end e-commerce data engineering and business intelligence pipeline using Databricks.

It processes source CSV files, cleans and transforms data, creates analytical tables, and presents business insights through SQL queries, Databricks Genie AI, and interactive dashboards.

## 2. Problem Statement

Processing growing e-commerce datasets using separate local scripts can lead to memory limitations, inconsistent data formats, slow reporting, and manual pipeline execution.

This project addresses these challenges by using distributed data processing, structured data governance, a Medallion architecture, and automated workflow orchestration.

## 3. Architecture

Source CSV Files → Unity Catalog and Volume → Bronze → Silver → Gold → Analytics View → Genie AI and Dashboard

Databricks Workflows coordinate processing tasks and validation.

## 4. Technologies Used

- Databricks
- PySpark
- Python
- SQL
- Delta Lake
- Unity Catalog
- Databricks Genie AI
- Databricks Dashboards
- Databricks Workflows
- Git and GitHub

## 5. Medallion Architecture

### Bronze
Ingests source data into Delta tables and preserves ingestion metadata.

### Silver
Cleans and standardizes records, handles data types, and applies data quality rules.

### Gold
Creates business-ready dimensions and fact tables, calculates sales measures, and prepares data for analysis.

## 6. Analytics and Visualization

The project uses a unified analytics view to support business queries and dashboard visualizations, including monthly sales trends, category sales, and day/hour sales patterns.

## 7. Documentation

Refer to the `documentation` folder for the project handbook, problem statement, architecture flowchart, and detailed explanations.

## 8. Repository Structure

- `notebooks/` — Databricks notebook source code
- `sql/` — SQL queries and validation scripts
- `documentation/` — Project documentation

## 9. Validation

Data quality checks and SQL comparisons are used to validate row counts, keys, calculations, and reporting totals.

## 10. Notes

The repository documents the project implementation. Actual results depend on the source data, workspace configuration, and execution environment.
