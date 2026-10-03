# Operational Performance Dashboard

A Power BI portfolio project for analyzing operational performance across countries, platforms, and reporting periods.

The dashboard focuses on three main business areas:

- Output performance
- Lot size analysis
- Sample request activity

It allows users to interactively filter the data by platform, country, and year, and switch the output trend between yearly, quarterly, and monthly reporting views.

The dataset used in this project is fully synthetic and was created for portfolio purposes. The dashboard is inspired by management-reporting and KPI-analysis workflows.

---

## Dashboard Preview

![Operational Performance Dashboard](Dashboard.png)

---

## Key Features

### KPI Summary

The dashboard provides a high-level overview of:

- Total Output Volume
- Total Sample Requests
- Average Lot Size

### Output Analysis

- Output volume comparison across countries
- Interactive output trend analysis
- Year / Quarter / Month reporting-period selector
- Platform, country, and year filters

### Lot Size Analysis

Compares the following metrics across countries:

- Maximum Lot Size
- Minimum Lot Size
- Average Lot Size

### Sample Request Analysis

Compares sample activity by country using:

- Fast Track Samples
- Additional Samples

### Dynamic Key Insights

The dashboard automatically identifies the current top-performing country based on the selected filters:

- Top Output Country
- Top Average Lot Size
- Top Sample Requests

These insights are calculated dynamically using DAX and update when the user changes the report filters.

---

## Tools and Skills Demonstrated

- Microsoft Power BI
- DAX Measures
- Data Modeling
- Excel Data Preparation
- KPI Reporting
- Interactive Slicers
- Field Parameters
- Dynamic Filter Context
- Data Visualization
- Business Performance Analysis

---

## Interactive Reporting

The dashboard supports filtering by:

- Platform
- Country
- Year

The **Year / Quarter / Month** selector in the Output Trend visual allows users to change the reporting granularity without using separate charts for each reporting period.

---

## Project Files

- `Business_KPI_Performance_Dashboard.pbix`  
  Interactive Power BI report

- `Business_KPI_PowerBI_Source.xlsx`  
  Synthetic source dataset used for the analysis

- `Dashboard.png`  
  Preview of the completed dashboard

---

## Project Purpose

The purpose of this project was to create a clean and interactive management-style dashboard that transforms operational data into an easy-to-understand KPI reporting view.

The project demonstrates how Power BI can be used to:

- Monitor business performance
- Compare performance across countries
- Analyze trends over different reporting periods
- Identify high-performing regions dynamically
- Present management KPIs in a structured and visually consistent format

---

## Note

This project uses synthetic data and does not contain confidential or proprietary company information.
