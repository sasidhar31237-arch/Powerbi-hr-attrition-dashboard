# HR Attrition Analysis Dashboard (Power BI)

Interactive Power BI dashboard analyzing a 1,470-employee HR dataset to visualize attrition patterns.

## Dashboard Preview


(screenshot 2026-07-24 08525.png)



## Features
- KPI cards showing overall attrition rate (16%) and total employee count (1,470)
- Bar chart: Attrition rate by department
- Bar chart: Average monthly income by job role
- Matrix (cross-tab): Attrition rate by department and job role
- Interactive slicers: Department and Gender (hierarchical filtering)

## Techniques Used
- DAX measures (CALCULATE, DIVIDE, COUNTROWS) for dynamic attrition rate calculation
- Matrix visual for multi-dimensional analysis
- Interactive cross-filtering via slicers

## Key Findings
- Sales and HR departments show the highest attrition rates
- Research & Development has the largest workforce but lowest attrition
- Overall company attrition rate: 16%

## Dataset
IBM HR Analytics Employee Attrition dataset (Kaggle, 1,470 rows, 35 columns)
