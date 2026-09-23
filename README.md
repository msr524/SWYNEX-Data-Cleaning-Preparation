# SWYNEX-Data-Cleaning-Preparation

## Overview
This repository contains the completed **Task 1: Data Cleaning & Preparation** for the SWYNEX Technologies internship. The objective of this project is to process a raw, messy public dataset across three different tools—**Python**, **SQL**, and **Excel**—and transform it into a clean, reliable, and analysis-ready format.

---

## Tools & Technologies Used
To demonstrate a thorough approach to data engineering and preparation, three different workflows were implemented:

* **Microsoft Excel**: Used for initial visual data profiling, quick sorting, conditional formatting, structural filtering, and bulk updates using Find & Replace.
* **Python (Pandas)**: Used for programmatic inspection, handling missing values, automated type casting, and executing scalable DataFrame transformations.
* **SQL**: Used for querying raw tables, handling text formatting, filtering null values, and removing duplicates using window functions (`ROW_NUMBER()` / `QUALIFY`).

---

## Data Cleaning Steps Performed
 across all three approaches, the raw dataset's anomalies were systematically addressed:

1. **Handling Missing Values & Errors**: 
   * Identified and filtered out or replaced corrupted entries containing `UNKNOWN`, `N/A`, and `ERROR` strings.
   * Imputed or dropped missing cells across key columns to prevent bias during downstream analysis.

2. **Removing Duplicate Records**:
   * Detected and eliminated exact and partial duplicate rows to ensure data integrity and accurate aggregations.

3. **Correcting Data Types**:
   * Converted misclassified text columns into proper numeric, date/time, and categorical data types to enable accurate mathematical calculations.

4. **Standardizing Inconsistent Text & Formatting**:
   * Cleaned trailing and leading white spaces, standardized text casing (Lower/Upper/Title Case), and resolved spelling typos in categorical fields.

---

## Repository Structure & Included Files
