# Business Analytics Dashboards (Power BI)

[![Power BI](https://img.shields.io/badge/Power%20BI-Data%20Viz-F2C811?logo=powerbi&logoColor=000)](#)
[![Excel](https://img.shields.io/badge/Excel-Data%20Source-217346?logo=microsoft-excel&logoColor=fff)](#)
[![Status](https://img.shields.io/badge/Status-Active-2ea44f)](#)

Interactive Power BI dashboards with supporting Excel data for financial budgeting, variance analysis, and sales KPIs with forecasting.

---

## Table of contents
- [Dashboards](#dashboards)
- [Features](#features)
- [Quick start](#quick-start)
- [Folder structure](#folder-structure)
- [Data sources](#data-sources)
- [Customization](#customization)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)

## Dashboards

- Finance — Budgeting & Variance Analysis (`Finance_data/FINACIAL BUDGETTING & VARIANCE ANALYSIS TOOL.pbix`)
- Sales — KPIs & Forecasting (`Sales Dashboard/SALES DASHBOARD AND FORECASTING.pbix`)

> Optional: Add screenshots to an `assets/` folder and uncomment the lines below.
<!--
### Preview

![Finance Dashboard](assets/finance-dashboard.png)
![Sales Dashboard](assets/sales-dashboard.png)
-->

## Features

### Finance: Budgeting & Variance Analysis
- Budget vs. Actuals with variance breakdown (absolute and %)
- Period-over-period comparisons (MoM, QoQ, YoY)
- Drill-through to account/category details
- Parameterized scenarios (best/base/worst) where applicable

### Sales: KPIs & Forecasting
- Core KPIs (Revenue, Units, AOV, Conversion)
- Category/Region/Product performance
- Trend analysis with built-in Power BI forecasting
- Filters and slicers for ad‑hoc analysis

## Quick start

1. Install Power BI Desktop (latest) and Microsoft Excel.
2. Open one of the `.pbix` files in Power BI Desktop:
   - `Finance_data/FINACIAL BUDGETTING & VARIANCE ANALYSIS TOOL.pbix`
   - `Sales Dashboard/SALES DASHBOARD AND FORECASTING.pbix`
3. If prompted for data source permissions or file paths:
   - Keep the paired `.xlsx` files in the same folders, or
   - Update the path via Transform data → Data source settings.
4. Refresh the report (Home → Refresh).

## Folder structure

```
.
├─ Finance_data/
│  ├─ FINACIAL BUDGETTING & VARIANCE ANALYSIS TOOL.pbix
│  └─ Financial_Budgeting_Sheets.xlsx
└─ Sales Dashboard/
   ├─ SALES DASHBOARD AND FORECASTING.pbix
   └─ Sample_Sales_Data.xlsx
```

## Data sources

- Excel files are provided as samples to explore the dashboards.
- Replace with your own data and re‑point the data source in Power BI if needed.

## Customization

- Add/remove visuals in the `.pbix` to match your KPIs.
- Create or update measures with DAX for custom calculations.
- Use a dedicated Date table for accurate time intelligence.

## Troubleshooting

- Missing data: Verify the Excel file path under Data source settings.
- Refresh issues: Check file permissions and that the workbook is not open/locked.
- Time intelligence: Ensure an active relationship between your Date table and fact tables.

## Contributing

1. Fork this repository and create a feature branch.
2. Commit your changes with a clear message.
3. Open a pull request describing the change and screenshots if UI updates.

## License

Choose and add a license in a `LICENSE` file (e.g., MIT, Apache‑2.0). If unsure, see `https://choosealicense.com`.
