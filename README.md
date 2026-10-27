# Sales Analysis Dashboard — Power BI

A university data analytics assignment built in Microsoft Power BI, focused on sales performance, profitability, product categories, returns, and geographic and time-based analysis.

## Contents

- `omarpro.pbix` — original Power BI report.
- `data/Database.rar` — original source-data archive with CSV tables.
- `docs/assignment-specification.pdf` — original final-exam requirements (reference, not a claim of full completion).

## Report overview

Inspection of the PBIX report layout confirms three report pages:

| Page | Visual count |
| --- | ---: |
| Main | 14 |
| Map | 1 |
| Time series | 2 |

The assignment specification covers Power Query data preparation, relational modeling, DAX measures for revenue, costs, profit and returns, dashboard KPIs, geographic analysis, and time-series/what-if exercises. These are **assignment requirements**; their implementation and numerical correctness have not been fully audited.

## Data

The `Database.rar` archive contains `Sales_Orders.csv`, `Inventory_Items.csv`, `Item_Categories.csv`, `Item_Subcategories.csv`, `Return_Transactions.csv`, `Sales_Regions.csv`, `Calendar.csv`, and client CSVs. The archive has not been verified as the exact active source of every Power BI query. Open the PBIX in Power BI Desktop and verify data source paths and refresh settings.

## How to open

1. Install Microsoft Power BI Desktop.
2. Open `omarpro.pbix`.
3. If refresh fails, extract `data/Database.rar` locally and update the Power Query source paths.
4. Inspect relationships, DAX measures, visuals and filters before presenting quantitative conclusions.

## Limitations

- Report visuals and model calculations have not been fully validated against the rubric.
- Forecast settings and what-if behavior require verification in Power BI Desktop.
- Data provenance and permission to redistribute the underlying dataset should be confirmed before making this repository public.

## Tools

Microsoft Power BI, Power Query, DAX, CSV data sources.
