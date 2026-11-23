# HERVeg.05 — 2026 Financial Governance & Expense Dashboard

## Project Overview
This project transforms an unstandardized Q1 2026 transaction ledger into an automated, relational financial control tool built in Microsoft Excel. Designed for HERVeg.05, this dashboard enables management to monitor programmatic spending, track actuals against budget targets, measure cash runway, and spot financial risks automatically.

## Executive Dashboard Preview

(dashboard_overview.png)


## Key Analytical & Technical Features

Automated Data Pipeline: Standardized inconsistent date strings and text casing into a structured Excel Table (`Clean_Transactions`).

Relational Program Mapping: Built a dedicated `Metadata` tab linked via `XLOOKUP` to dynamically map program codes (`OPS`, `PROD-VEG`, `MKT`, `DIST`) to full department names.

Dynamic Summary Matrix: Engineered multi-criteria `SUMIFS` formulas to aggregate spending by category and month without manual intervention.

Cash Runway & Burn Rate KPIs: Modeled average monthly cash burn ($9,760/mo) against starting cash reserves to track real-time survival runway.

Automated Risk Alerts: Applied Conditional Formatting rules to instantly flag budget overruns in red and on-target categories in green.

Self-Service Documentation: Included a `ReadMe_UserGuide` tab and version change log so the management team can maintain and append new transactions independently.


## Clean Data Architecture

(clean_ledger.png)


## How to Use This File
1. Click on `HERVeg05_2026_Financial_Dashboard.xlsx` in the file list above.
2. Click the Download raw file icon to open the interactive workbook in Microsoft Excel.
3. Review the `ReadMe_UserGuide` tab first for instructions on adding new monthly transactions.

