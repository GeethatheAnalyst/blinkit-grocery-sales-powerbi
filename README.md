# Blinkit Grocery Sales Dashboard — Power BI

This was my first proper Power BI project. The dataset is a publicly available grocery sales dataset based on Blinkit's product and outlet data (sourced from Kaggle). I built this to practise creating dashboards that actually tell a story — not just charts thrown together on a page.
---


## Dataset used

- <a href="https://github.com/GeethatheAnalyst/blinkit-grocery-sales-powerbi/blob/main/BlinkIT%20Grocery%20Data.xlsx">Dataset</a> | Raw dataset used in this project — source: Kaggle
---

## What I was trying to find out

- Which product categories drive the most revenue?
- Does fat content (Low Fat vs Regular) affect sales or customer ratings?
- Which outlet type and location tier performs best?
- How have sales trended over time since outlets were established?
---

## What I built

The dashboard has 4 pages — each one answers a different layer of the business question.

**Page 1 — Main Overview**
The landing page with the full picture. Four KPI cards at the top: 1.20M total sales, 141 average sales per item, 2K unique items, and 33K total ratings. Below that, a breakdown of sales by outlet type and fat content, a trend chart by outlet establishment year, and a Top 10 items table on the right.

**Page 2 — Filtered View (Rating = 5)**
This page shows what the dashboard looks like with the Rating 5 filter applied — isolating only the top-rated transactions. Total sales drop to 96.4K with 560 unique items. Snack Foods moves to the top of the rankings at 14,018.70, overtaking Fruits & Vegetables. A good example of how interactive filters change the story the data tells.

**Page 3 — Outlet Data**
Focuses on the outlet side of the business. Supermarket Type 1 dominates with 788K in sales — almost 5x the next outlet type. The donut chart shows Medium outlets make up the largest share (42.6%) by count. The sales forecast visual shows the peak was 2018 at 204.52K and the trend has been steadier since.

**Page 4 — Items Data**
Drills into the product side. The bar chart ranks all item categories by total sales — Fruits & Vegetables leads at 178K, just ahead of Snack Foods at 175K. Also shows total ratings split by fat content (Low Fat: 22K, Regular: 12K) and max sales by fat content — both sit at 267, which tells you fat content alone doesn't determine a product's ceiling
---

## Key findings

- Fruits & Vegetables (178K) and Snack Foods (175K) are the top 2 revenue categories overall — but when filtered to Rating 5 only, Snack Foods pulls ahead
- Supermarket Type 1 accounts for ~65% of all outlet sales
- Tier 2 locations outperform Tier 1 and Tier 3 in total sales for Supermarket Type 1
- Sales peaked in 2018 at 204.52K and have stabilised around 130K since
- Low Fat and Regular items both have the same max sales value (267) — fat content doesn't determine a product's sales ceiling
- Regular fat items account for 64.6% of total sales by value despite lower average ratings

---

## Tools used

- Power BI Desktop
- DAX (calculated measures for KPIs and rankings)
- Power Query (data cleaning and transformations)
- Interactive slicers (Rating, Item Type, Outlet Location, Outlet Size, Outlet Type)

---
- <a href="https://github.com/GeethatheAnalyst/blinkit-grocery-sales-powerbi/blob/main/Blinkit%20Power%20Bi%20Assignment-2.pbix"> The Power BI source file</a> — open with Power BI Desktop to explore the full interactive dashboard



