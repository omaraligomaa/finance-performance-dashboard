# Report Structure

## Financial Dashboard

The main dashboard page provides an executive view of financial performance using KPI cards, charts, slicers, and variance indicators.

Core analytical areas include:

- Revenue performance
- Expenditure performance
- Net income
- Actual vs. prior year comparison
- Variance monitoring
- Organization analysis
- Time filtering by year, quarter, and month

## Balance Sheet

The balance sheet page focuses on balance values and year-over-year comparisons.

The report references measures such as:

- Balance Actual
- Balance LY Actual
- Balance YOY Variance
- Balance Actual Card
- Balance LY Actual Card
- Balance Actual Value
- Balance LY Actual Value
- Balance Variance Indicator
- Balance Color Indicator

## Income Statement Report

The income statement page provides structured financial-statement reporting using account hierarchy levels.

The report references:

- Income Statement Matrix Actual Value
- Income Statement Matrix Budget Value
- Income Statement Achievement %
- Income Statement Indicator
- Income Statement Indicator Value
- Income Statement LY Actual

## Model Entities Referenced by the Report

- `MeasuresTable`
- `DimDate`
- `DimAccount`
- `DimOrganization`

## Hierarchies and Attributes Used

The report uses fields including:

- Account hierarchy levels: Level 2 through Level 6
- Account Type
- Organization Name
- Calendar Year
- Quarter
- Month

## Visual Components

The PBIX includes a combination of:

- KPI cards
- Clustered bar charts
- Clustered column charts
- Pivot / matrix-style visuals
- Slicers
- Navigation buttons
- Supporting shapes and layout elements
