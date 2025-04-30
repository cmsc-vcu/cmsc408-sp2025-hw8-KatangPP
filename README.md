# CMSC 408 - Homework 8  
## World Bank Indicator Analysis

This repository contains my submission for Homework 8 in CMSC 408: Database Systems. The goal of this assignment is to analyze and manipulate a real-world dataset from the **World Bank’s World Development Indicators (WDI)** using SQL and Python within a Quarto report.

---

## Overview

The World Bank’s WDI dataset contains key metrics on development, including economic performance, education, health, and income classifications. In this assignment, I explored various aspects of the `wdi_country` table, including:

- Identifying and filtering actual countries vs. regions or aggregates.
- Grouping and summarizing income levels across regions.
- Investigating anomalies and correcting missing or inaccurate values.
- Creating pivot-style summary tables for better insight.
- Calculating percentages and regional distributions for different income groups.

---

## Skills Demonstrated

- Writing advanced SQL queries involving `GROUP BY`, `CASE`, subqueries, and `CTE`s.
- Creating derived tables using `CREATE TABLE ... SELECT`.
- Performing data validation and correction through `UPDATE` queries.
- Using Quarto with Python to render SQL results in HTML reports.
- Combining aggregation and filtering logic for data analysis.

---

## Project Files

- `report.qmd`: Quarto report containing all SQL queries, output tables, and reflections.
- `README.md`: This file.
- `.env`: Contains database credentials (excluded from repo).
- Python helper files: Used to connect to the database and render results.

---

## Running the Report

To render the report:

```bash
quarto render report.qmd
