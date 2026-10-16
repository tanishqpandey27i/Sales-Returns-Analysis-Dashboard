# Sales & Returns Analysis Dashboard

An interactive **Power BI dashboard** for exploring sales performance, profitability, order volume, and product returns. The report brings high-level KPIs and breakdowns by time, product category, customer, geography, market, and shipping days into one place.

## Overview

The dashboard is designed to help users monitor overall sales and return performance, spot patterns across business segments, and move from summary metrics to country-level details.

## Key Metrics

- **Total Sales** — overall sales value represented in the report.
- **Total Orders** — order volume represented in the report.
- **Total Returns** — total returns represented in the report.
- **Return Percentage** — the return-rate measure available in the report.
- **Total Profit** — profit measure used to compare performance over time.

> The dashboard displays these measures from its embedded Power BI data model. For the exact calculation logic, review the measure definitions in Power BI Desktop.

## Dashboard Features

### Main Page — Return Analysis

- KPI cards for Total Sales, Total Orders, Total Returns, and Return Percentage.
- A **Year slicer** to focus the report on a selected year.
- Returns by product category.
- Sales and profit trends by year and month.
- Return breakdowns by customer, region, and shipping days.
- Return percentage by market, with product category as an additional breakdown.
- Sales by city.

### Details Page

A country-level table with the following measures and fields:

- Country
- Total Sales
- Return Percentage
- Total Orders
- Total Returns

Use this page to examine country-level performance alongside the headline KPIs.

## Tools & Data Model

- **Visualization and reporting:** Microsoft Power BI Desktop
- **Report format:** `.pbix`
- **Model entities referenced by the report:** `Orders`, `Products`, and `DateTable`
- **Analysis dimensions:** time, product category, customer, region, shipping days, market, city, and country

The underlying data and measure calculations are packaged in the Power BI report. The original external data-source details are not documented here, so confirm the source and refresh settings in Power BI Desktop before republishing or refreshing the report.

## How to Use

1. Open `SALES DASHBOARD.pbix` in **Power BI Desktop**.
2. Start on the **Main Page / Return Analysis** view to review the KPI cards and charts.
3. Use the **Year** slicer to filter the analysis to the period you want to inspect.
4. Compare sales, profit, and return patterns across the available charts.
5. Open the **Details** page to review country-level results.
6. Select chart elements to explore the report's interactive filtering and cross-highlighting behavior.

## Potential Extensions

- Add targets and year-over-year comparisons for sales, profit, orders, and returns.
- Add drill-through pages for product and customer-level investigation.
- Include clearer metric definitions and data-refresh notes for business users.
- Add data-quality checks for missing dates, duplicate orders, and inconsistent return records.

## Notes

This README describes the report structure and fields visible in the `.pbix` file. Results depend on the underlying dataset, model relationships, filters, and measure definitions. Validate these before using the dashboard for operational or financial decisions.
