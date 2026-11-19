# E-commerce Sales Performance Dashboard

## Project Overview

An interactive e-commerce sales dashboard built using **Google Looker Studio**, based on the Brazilian Olist E-commerce dataset.

This project focuses on sales performance, delivered orders, average order value, and product category analysis. The dashboard presents key business metrics through clear, interactive visualizations.

## Tools & Technologies

- **Google Looker Studio** — Dashboard development and data visualization
- **PostgreSQL** — SQL queries and data aggregation
- **Google Sheets** — Data preparation and connection to Looker Studio
- **SQL** — Joins, filtering, grouping, and KPI calculations

## Key Performance Indicators

| KPI | Value |
|---|---:|
| Total Order Value (Including Freight) | 15,419,773.75 |
| Delivered Orders | 96,478 |
| Average Order Value (AOV) | 159.83 |

*All KPIs are calculated using delivered orders. Total Order Value includes freight charges and does not represent profit.*

## Dashboard Visualizations

1. **Monthly Order Value Trend** — Tracks changes in order value over time.
2. **Monthly Delivered Orders** — Shows monthly delivered order volumes.
3. **Top 10 Product Categories by Revenue** — Identifies categories generating the highest product revenue, excluding freight.
4. **Top 10 Product Categories by Items Sold** — Compares product categories by sales volume.

## Key Insights

- The highest monthly order value occurred in **November 2017**.
- **beleza_saude** (Health & Beauty) generated the highest product revenue.
- **cama_mesa_banho** (Bed, Bath & Table) recorded the highest number of items sold.
- Average order value across delivered orders was **159.83**.

## Data Workflow

1. Extracted and aggregated Olist data using PostgreSQL.
2. Exported monthly sales and product category summaries as CSV files.
3. Imported the datasets into Google Sheets.
4. Connected Google Sheets to Looker Studio.
5. Created and validated dashboard KPIs against SQL results.

## Dataset

Brazilian E-commerce Public Dataset by Olist.

## Related Project

[View the PostgreSQL E-commerce Analysis Project](https://github.com/itsfaraan/ecommerce-sql-analysis)

## Dashboard Preview

A PDF export of the dashboard is available in this repository.
![Dashboard Preview](Screenshot%202026-11-19%20at%2011.35.24.png)
