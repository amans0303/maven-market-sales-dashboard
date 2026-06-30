# maven-market-sales-dashboard
# Maven Market Power BI Dashboar

An interactive Power BI dashboard built to track and analyze the topline performance of **Maven Market**, a retail chain operating across North America (USA, Canada, and Mexico). The dashboard consolidates raw transactional data into a single, easy-to-read view for store managers and stakeholders to monitor sales, profitability, and returns.

## Overview

The dashboard answers key business questions such as:
- How are transactions, profit, and returns trending this month vs. last month and vs. goal?
- Which product brands are driving the most profit and which have the highest return rates?
- How is performance distributed geographically across stores in the USA, Canada, and Mexico?
- What does weekly revenue look like over time, and are there seasonal patterns?
- How close is the business to hitting its overall revenue target?

## Dashboard Features

- **KPI Cards** — Current Month Transactions, Current Month Profit, and Current Month Returns, each compared against a goal with trend sparklines.
- **Product Brand Performance Table** — Ranks brands by Total Transaction, Total Profit, Profit Margin, and Return Rate, with conditional formatting (data bars) for quick visual scanning.
- **Store Country Slicer** — Filter the entire report by store country (All, Canada, Mexico, USA).
- **Geographic Map** — Bubble map showing transaction volume by store location across North America.
- **Total Transaction by Store Country** — Bar chart breaking down transaction share between USA, Canada, and Mexico.
- **Weekly Revenue Trending** — Time series chart of weekly revenue across the reporting period, used to spot seasonality and growth trends.
- **Revenue vs Target Gauge** — Tracks cumulative revenue progress against the overall revenue goal.

## Tools & Skills Used

| Tool | Purpose |
|---|---|
| **Power BI Desktop** | Report design, visuals, and dashboard layout |
| **Power Query** | Data cleaning, transformation, and shaping raw source data into model-ready tables |
| **DAX** | Custom measures for KPIs (Profit Margin, Return Rate, period-over-period comparisons, goal tracking) |
| **Data Modeling** | Built a structured relational model (fact and dimension tables — transactions, products, stores) to support efficient and accurate querying |

## Key Insights Derived

- A small set of top-performing brands (e.g., Hermanos, Tell Tale, Ebony) account for a disproportionate share of total profit, suggesting opportunities for focused inventory and marketing investment.
- Return rates vary notably by brand, with some brands (like Horatio) showing higher return rates relative to their profit margin — a potential quality or fulfillment issue worth investigating.
- The USA contributes the overwhelming majority of total transactions compared to Canada and Mexico, indicating where current revenue concentration lies and where growth opportunity may exist in underpenetrated markets.
- Weekly revenue shows clear seasonal spikes, useful for forecasting and inventory/staffing planning.

## Screenshots/Demo
Example: ![Dashboard Preview].(https://github.com/amans0303/maven-market-sales-dashboard/blob/main/image.png)
