# Healthcare Claims Analysis – Excel

## Project Overview

This project analyzes a fully synthetic healthcare claims dataset using Microsoft Excel. The goal was to practice data cleaning, lookup functions, PivotTables, conditional formatting, calculations, visualization, and turning raw claims data into useful business insights.

The dataset contains 60 fictional healthcare claims and does not contain any real patient information.

## Skills Used

- Excel Tables
- Filtering and sorting
- XLOOKUP
- Conditional Formatting
- PivotTables
- PivotCharts
- Data validation
- Basic formulas
- Healthcare claims analysis
- Data interpretation and reporting

## Analysis Performed

I analyzed the dataset to answer questions such as:

- How much was billed compared with how much was paid?
- Which payers had the highest billed and paid amounts?
- What were the most common reasons for claim denials?
- Which provider specialties had the longest claim processing times?
- How much money remained outstanding on individual claims?

I also used XLOOKUP to connect claim records with provider specialty, provider region, and CPT descriptions from separate lookup tables.

## Key Findings

- Sports Medicine had the longest average claim processing time at **36.25 days**, compared with an overall average of **24.67 days**.
- Missing Prior Authorization was the most common denial reason, representing **4 of 15 denied claims**.
- Total billed amount was **$37,161.81**, while total paid amount was **$14,527.44**.
- Approximately **39.1% of billed charges were paid** in the dataset.
- The difference between billed and paid amounts was **$22,634.37**.
- Diagnostic Imaging had the fastest average processing time at **19.33 days**.

## Excel Workbook

The completed Excel workbook is included in this repository:

`Meluu_healthcare_Claims_Analysis.xlsx`

The workbook includes:

- Raw claims data
- Provider lookup data
- CPT code lookup data
- Calculated fields
- PivotTables
- Charts
- Key findings

## Visualizations

### Billed vs. Paid Amount by Payer

This chart compares total billed charges with total payments received across insurance payers.

### Denied Claims by Reason

This chart shows the frequency of each claim denial reason and highlights the most common causes of denied claims.

## What I Learned

This project helped me build practical experience working with structured business data in Excel. I became more comfortable using XLOOKUP to combine information across datasets, creating PivotTables to summarize large datasets, using conditional formatting to identify important records, and turning analysis into clear business findings.

## Disclaimer

This project uses a completely synthetic dataset created for educational and portfolio purposes. It contains no real patient data or protected health information (PHI).
