## 📊 Dashboard Preview

![Global Superstore Sales Dashboard](images/dashboard-preview.png)
# Global Superstore Sales Performance Dashboard

## Project Overview

This project transforms the Global Superstore transactional dataset into an
interactive Excel-based sales performance dashboard.

The project involved data validation and preparation, data modeling,
lookup-table creation, PivotTable analysis, KPI development, PivotCharts,
and interactive slicers.

The final dashboard provides an overview of revenue, orders, category
performance, yearly trends, regional performance, sub-category performance,
and returned orders.

RAW DATA
   ↓
DATA CLEANING & VALIDATION
   ↓
DATA STRUCTURING
   ↓
LOOKUP / SUPPORT TABLES
   ↓
DATA MODEL & RELATIONSHIPS
   ↓
PIVOTTABLE ANALYSIS
   ↓
KPI CALCULATIONS
   ↓
PIVOTCHARTS
   ↓
SLICERS / TIMELINE
   ↓
FINAL DASHBOARD


## 🎯 Business Objectives

- Monitor total revenue
- Analyze yearly revenue trends
- Compare revenue by category
- Analyze sub-category performance
- Identify high-performing regions
- Analyze returned orders
- Monitor return rate

## 🛠 Tools & Technologies

- Microsoft Excel
- Advanced Excel
- PivotTables
- Power Pivot
- Data Model
- Relationships
- GETPIVOTDATA
- Slicers
- PivotCharts
- KPI Cards

## 📈 Dashboard Features

- Total Revenue
- Total Orders
- Returned Orders
- Return Rate
- Yearly Revenue Trend
- Revenue by Category
- Revenue by Sub-Category
- Revenue by Region
- Returned Orders by Category
- Interactive Slicers

## 📁 Files

| File | Description |
|---|---|
| Excel Dashboard | Interactive Excel dashboard |
| Dashboard Preview | Static dashboard preview |

## 🚀 How to Use
Download the Excel workbook from the dashboard folder.
Open the workbook using Microsoft Excel.
Navigate to the Dashboard sheet.
Use the Category slicer to filter product categories.
Use the Region slicer to filter geographical performance.
Use the Order Date timeline to analyze different time periods.
Review the KPI cards and PivotCharts.
Explore the PivotTables sheet for detailed analytical results.
Review the supporting tables and Data Model relationships if required.

Note: Microsoft Excel desktop is recommended because the workbook uses
Power Pivot/Data Model relationships, PivotTables and interactive slicers.

## 📌 Key Skills Demonstrated
Data cleaning
Data quality validation
Data transformation
Data structuring
Data modeling
Relational data modeling
Lookup table creation
Data validation
PivotTable analysis
PivotChart development
KPI design
GETPIVOTDATA
Interactive dashboard development
Slicer implementation
Time-series analysis
Regional analysis
Category analysis
Business reporting
Data visualization

- ### 1. Raw Data Assessment
The original Orders dataset contained 51,290 transaction-level rows and 25
business fields. The dataset was reviewed to understand its grain, keys,
dimensions, and measures.

### 2. Data Quality Validation
- Checked business columns for missing values.
- Validated date fields and date ranges.
- Verified numeric fields such as Sales, Quantity, Discount, Profit and
  Shipping Cost.
- Confirmed Row ID uniqueness.
- Distinguished repeated Order IDs from true duplicates because the dataset
  is transaction-level.

### 3. Returns Data Preparation
The Returns table contained 1,079 unique returned Order IDs. Order ID was
used as the key for linking return information with transactional sales data.

### 4. Supporting Tables
Supporting structures were maintained for People, Region and Order IDs.
An Order Lookup table containing 25,728 distinct Order IDs was created to
support the Data Model.

### 5. Regional Transformation
A Region Group field was created to provide additional regional
classification, including Eastern Canada and Western Canada.

### 6. Data Model
The cleaned and structured tables were incorporated into Excel's Data Model
and connected through appropriate relationships.

### 7. Analytical Layer
PivotTables were created for:
- Total Revenue
- Sales by Category
- Yearly Sales
- Revenue by Sub-Category
- Revenue by Region
- Returned Orders

### 8. Dashboard Layer
The analytical results were presented through KPI cards, PivotCharts,
slicers and an Order Date timeline to create an interactive sales
performance dashboard.
## 🧩 Key Challenges & Solutions

### Challenge 1 — Transaction-level data
The Orders table contains multiple rows per Order ID.

**Solution:** Order ID was not treated as a row-level unique key in the
transaction table. A distinct Order Lookup structure was created for
order-level analysis.

### Challenge 2 — Multiple source tables
Sales, Returns and People information were stored separately.

**Solution:** A Data Model was created to connect the tables through
appropriate keys and relationships.

### Challenge 3 — Regional classification
Canada required additional regional classification.

**Solution:** A Region Group field was created to distinguish Eastern and
Western Canada while retaining the original Region field.

### Challenge 4 — Interactive reporting
The dashboard needed to respond to user selections.

**Solution:** PivotTables were connected to Category and Region slicers and
an Order Date timeline through Report Connections.

### Challenge 5 — KPI consistency
Dashboard KPIs needed to remain connected to the analytical layer.

**Solution:** GETPIVOTDATA-based formulas were used instead of manually
entered KPI values.

## 📊 Project Outcome

The final deliverable transforms a large transaction-level dataset into an
interactive sales performance reporting system.

The dashboard enables users to quickly monitor revenue, orders, returns,
category performance, yearly trends, sub-category performance and regional
performance through a single interactive interface.

The project demonstrates the complete analytical workflow from raw data
preparation and relational data modeling to business-focused visualization
and interactive reporting.


