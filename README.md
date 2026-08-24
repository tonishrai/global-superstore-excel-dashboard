# Global Superstore Sales Analysis (Excel)

Interactive Excel dashboard analyzing sales, profit, and regional performance for the Global Superstore dataset, using pivot tables and charts.

## Overview

- **Dataset:** 51,290 orders across 24 fields (order details, geography, category, sales, profit, discount, shipping)
- **Time period:** 2011–2014
- **Tools used:** Excel (Pivot Tables, Pivot Charts, formulas)

## Key Insights

- 💰 **$12.64M** in total sales generated **$1.47M** in profit overall
- 🏆 **Central** is the top-performing region — $2.82M in sales and $311K in profit, more than double the next-best region
- ⚠️ **Canada** underperforms significantly — just $17.8K profit despite meaningful sales volume, flagging a pricing or cost issue worth investigating
- 📉 **Tables (Furniture)** is actually losing money — **-$64K profit** on $757K in sales, likely driven by heavy discounting eating into margins
- 💻 **Technology** is the most profitable category ($663K profit), ahead of Office Supplies ($518K) and Furniture ($285K)

## What's in this repo

- `global-superstore-dashboard.xlsx` — the full interactive dashboard with pivot tables, charts, and slicers for region, category, and time period

## How I approached it

1. Cleaned and structured the raw order-level data
2. Built pivot tables to summarize sales and profit by region, category, sub-category, and market
3. Designed pivot charts to visualize regional performance and profit trends over time
4. Added slicers so the dashboard can be filtered interactively by year, region, and category

## Next steps I'd explore

- Investigate why Tables consistently loses money — is it discount policy or shipping cost?
- Break down Canada's underperformance by customer segment or product category
