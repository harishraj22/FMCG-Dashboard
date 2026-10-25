# FMCG Sales Performance Dashboard

An interactive, single-page Power BI report for exploring sales performance across products, categories, regions, and months.

![Dashboard screenshot](assets/Dashboard.png)

## What the report shows

- KPI cards for sales quantity, previous-month quantity, quantity change, item count, and YTD sales excluding the selected month.
- Slicers for month, category, and region.
- A product sales contribution bar chart.
- A selected-month product detail table with current and previous-month quantity and percentage change.
- A rolling seven-month quantity trend.
- Outlet sales and outlet rank within region.
- Dynamic metric and chart-axis selectors for exploring the data by time, SKU, or region.

## Data preparation and model

The source assessment workbook was cleaned in Power Query and modeled in Power BI with a sales fact table, dimension tables, and a marked Date table. DAX measures support the KPI cards and time-based comparisons. The source Excel workbook is not included in this repository package.

## Files

- `Assessment.pbix` - Power BI Desktop report and data model.
- `assets/Dashboard.png` - report screenshot.
- `assets/shop-background.png` - subtle report canvas background image.

## Open the report

Download `Assessment.pbix` and open it in Power BI Desktop. Use the month, category, region, chart metric, and chart axis controls to explore the report.

## Notes

The PBIX is an imported Power BI file and may contain a copy of the source data. Before making this repository public, confirm that the assessment dataset and report contents are cleared for public sharing. Do not upload credentials or private source files.
