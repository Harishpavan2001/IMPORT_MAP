# Import Data using Transform Maps (Spreadsheet)

## Project Overview
This project focuses on automating and streamlining data ingestion into **ServiceNow** using **Import Sets** and **Transform Maps**. Sample data is structured in a spreadsheet and loaded into ServiceNow import staging tables, where field mapping, data transformation, and duplicate prevention logic (coalescing) are applied before populating the target banking/custom table. Additionally, custom reports and visual dashboards are built to track and analyze the imported data.

---

## Team Members
* **Harishpavan A** (Team Leader)
* **Kalaiyarasan S**
* **Joe Sherwin J**
* **Jeeva G**
* **Logesh K**

---

## Modules & Key Features Implemented

### 1. Data Preparation & Table Creation
* **Spreadsheet Preparation:** Structured sample dataset containing core employee/banking fields (`Employee ID`, `Name`, `Email`, `Department`, `Location`).
* **Target Table Definition:** Created and configured custom target tables in ServiceNow to store processed data.

### 2. Import Set & Transform Mapping
* **Staging Area Setup:** Created ServiceNow Import Set tables to securely upload and validate raw Excel spreadsheet data (`.xlsx`).
* **Transform Map Configuration:** Mapped source spreadsheet columns to corresponding fields in the ServiceNow target table for accurate data transformation.

### 3. Data Transformation & Coalesce Validation
* **Execution of Transform Runs:** Processed raw data from import staging into final production tables.
* **Duplicate Prevention:** Configured **Coalesce** rules on unique key identifiers (e.g., `Employee ID`) to avoid duplicate record creation during subsequent re-imports.

### 4. Reporting & Dashboards
* **Data Visualization:** Built custom ServiceNow reports to analyze imported dataset trends and distributions.
* **Interactive Dashboards:** Assembled dynamic dashboards incorporating key metrics and visual reports for easy monitoring.
