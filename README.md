# FinSight Financial Analytics

### Financial Performance Analysis & Interactive Dashboard (2024–2025)

[![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow)](https://www.microsoft.com/en-us/download/details.aspx?id=58494)
[![DAX](https://img.shields.io/badge/Language-DAX-blue)](https://learn.microsoft.com/en-us/dax/dax-overview)
[![Status](https://img.shields.io/badge/Project-Completed-success)](https://github.com/ObiasamuelOche/finsight-financial-analytics/blob/main/Screenshot/Departmental-Analysis%202025.png)

## Project Overview

FinSight is a financial analytics project developed using Microsoft Power BI to evaluate the financial performance of a business over the 2024–2025 reporting periods.

The project transforms financial transaction data into interactive dashboards, providing insights into revenue performance, expense trends, profitability and departmental cost distribution.

The objective is to support management decision-making through data-driven financial analysis.

## Project Objectives

- Analyse revenue and expense performance.
- Evaluate gross and net profitability.
- Compare financial performance between 2024 and 2025.
- Identify major expense drivers.
- Examine departmental expense distribution.
- Provide actionable management recommendations.

## Tools and Technologies

| Tool | Application |
|---|---|
| [Microsoft Excel](https://www.microsoft.com/en-us/microsoft-365/excel) | Source financial dataset |
| [Power BI Desktop](https://www.microsoft.com/en-us/download/details.aspx?id=58494) | Data modelling and visualization |
| [DAX](https://learn.microsoft.com/en-us/dax/dax-overview) | Financial measures and calculations |
| [Microsoft Word](https://www.microsoft.com/en-us/microsoft-365/excel) | Project documentation |
| [GitHub](https://github.com/ObiasamuelOche/finsight-financial-analytics/tree/main) | Project hosting and portfolio presentation |

## Dashboard Pages

### 1. Executive Financial Overview

Provides a high-level summary of financial performance through KPI cards and monthly revenue and expense trends.

### 2. Profit and Loss Dashboard

Presents the income statement, including revenue, cost of sales, gross profit, operating expenses and net profit before tax.

### 3. Departmental and Cost Analysis

Examines departmental expenditure, expense accounts and major cost drivers across the two financial years.

## Key Financial Findings

- Revenue increased by approximately 52.63% between 2024 and 2025.
- Total expenses increased by approximately 68.09%.
- Gross profit increased only slightly despite revenue growth.
- Gross profit margin declined from approximately 16.74% to 11.67%.
- Net losses widened significantly in 2025.
- Diesel, freight and importation costs recorded substantial increases.
- Some expenses lacked departmental classification, highlighting a data-quality issue.

## Management Recommendations

1. Strengthen fuel consumption monitoring and procurement controls.
2. Review transportation routes and freight contracts.
3. Investigate importation and customs-related costs.
4. Improve procurement and inventory management.
5. Strengthen departmental expense classification.
6. Monitor profitability and expense growth regularly.

## Data Model

The Power BI model uses a central financial transaction fact table supported by dimension tables:

- FactFinancialTransactions
- DimAccount
- DimDepartment
- DimBranch
- DimCostCentre
- DimDate

DAX measures were developed for revenue, expenses, gross profit, net profit before tax, growth rates and profitability ratios.

## Data Source Acknowledgement

The financial dataset used in this project was provided by the course instructor for academic analysis.

The dataset is acknowledged as an instructor-provided resource and is not claimed as original data created by the project author.

## Project Files

- `FinSight_Financial_Analytics.pbix` – Interactive Power BI report.
- `FinSight_Financial_Performance_Analysis.docx` – Detailed financial analysis and management recommendations.
- `Screenshots/` – Dashboard visual previews.

## Author

**Obia Samuel Obia**

Information and Communication Engineering(ICE)  
Air Force Institute of Technology (AFIT)

## Conclusion

FinSight demonstrates how business intelligence tools can transform financial transaction data into meaningful insights.

The project highlights the importance of financial performance monitoring, expense management and data-driven decision-making.

*Turning financial data into meaningful business insights.*
