# Finance Performance Dashboard

A Power BI financial analytics project focused on monitoring financial performance through **Actual vs. Budget**, **year-over-year comparisons**, **variance analysis**, and structured financial statements.

## Project Overview

This project turns finance data into an interactive reporting layer for reviewing revenue, expenditures, net income, balance sheet performance, and organizational trends.

The Power BI report contains three main pages:

- **Financial Dashboard** — executive-level KPI and variance monitoring
- **Balance Sheet** — balance-focused analysis with current and prior-year comparisons
- **Income Statement Report** — structured income statement analysis

## Business Questions

The report is designed to answer questions such as:

- How is actual financial performance tracking against budget?
- How does current performance compare with the previous year?
- Where are the largest revenue and expenditure variances?
- How is net income changing over time?
- Which organizations or account groups contribute most to financial performance?
- What is the current position across the balance sheet and income statement?

## Data Model

The report uses a dimensional model built around finance reporting entities including:

- `DimDate`
- `DimAccount`
- `DimOrganization`
- `MeasuresTable`

The report also uses account hierarchy levels and date attributes to support drill-down analysis across financial statements and time periods.

## Key Measures

Examples of measures used in the report include:

- Revenue Actual
- Revenue LY Actual
- Revenue Variance
- Revenue Variance Indicator
- Expenditures Actual
- Expenditures LY Actual
- Expenditures Variance
- Net Income Actual
- Net Income LY Actual
- Net Income Variance
- Balance Actual
- Balance LY Actual
- Balance YOY Variance
- Income Statement Achievement %
- Income Statement Actual / Budget values
- KPI indicator and conditional-formatting measures

## Report Features

- Executive KPI cards
- Actual vs. Budget analysis
- Year-over-year comparison
- Revenue and expenditure variance analysis
- Balance sheet reporting
- Income statement reporting
- Organization-level analysis
- Account hierarchy drill-down
- Date filtering by year, quarter, and month
- Conditional KPI indicators
- Interactive slicers and navigation

## Tools & Technologies

- **Power BI Desktop**
- **DAX**
- **Power Query**
- **Microsoft Excel**
- **Dimensional Data Modeling**
- **Financial KPI Analysis**

## Repository Structure

```text
finance-performance-dashboard/
├── README.md
├── data/
│   └── Finance Dataset.xlsx
├── dashboard/
│   └── Finance Dashboard.pbix
└── docs/
    ├── report-structure.md
    └── measures.md
```

## Files

- `dashboard/Finance Dashboard.pbix` — Power BI report
- `data/Finance Dataset.xlsx` — source dataset
- `docs/report-structure.md` — report pages and model overview
- `docs/measures.md` — documented measure inventory

## Author

**Omar Ali**  
Data Engineering · Analytics Engineering

[LinkedIn](https://www.linkedin.com/in/eng-omargomaa) · [GitHub](https://github.com/omaraligomaa)
