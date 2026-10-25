# FMCG Sales Performance Dashboard

An interactive, single-page Power BI report for exploring sales performance across products, categories, regions, and months.


## What the report shows

- KPI cards for sales quantity, previous-month quantity, quantity change, item count, and YTD sales excluding the selected month.
- Slicers for month, category, and region.
- A product sales contribution bar chart.
- A selected-month product detail table with current and previous-month quantity and percentage change.
- A rolling seven-month quantity trend.
- Outlet sales and outlet rank within region.
- Dynamic metric and chart-axis selectors for exploring the data by time, SKU, or region.

## Data preparation and model

The source Dashboard workbook was cleaned in Power Query and modeled in Power BI with a sales fact table, dimension tables, and a marked Date table. DAX measures support the KPI cards and time-based comparisons. The source Excel workbook is not included in this repository package.

## Files

- `Dasboard.pbix` - Power BI Desktop report and data model.
- `Dashboard.png` - report screenshot.
- `shop-background.png` - subtle report canvas background image.

## Open the report

Download `Dashboard.pbix` and open it in Power BI Desktop. Use the month, category, region, chart metric, and chart axis controls to explore the report.

