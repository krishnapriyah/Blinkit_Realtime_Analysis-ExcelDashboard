
#  Blinkit Sales Performance Dashboard — Excel 

> *Analyzing India's Last Minute Delivery App sales data to uncover outlet performance, product trends, and customer preferences.*

## Project Overview

This project analyzes **8,523 sales records** from Blinkit (India's quick commerce grocery app) to understand what drives sales across different outlet types, locations, and product categories. The final output is an **interactive Excel dashboard** with slicers and pivot charts.

---
## Dashboard Preview

<img src="visuals/Blinkit_dashboard.png" width="100%" alt="Blinkit Sales Dashboard"/>

---

##  Business Problem

Blinkit operates across multiple outlet types and city tiers. The business needed answers to:

- Which outlet type and size generates the most revenue?
- Which product categories contribute the highest sales?
- How does fat content preference vary across outlet locations?
- Which city tier (Tier 1, 2, 3) performs best in total sales?
- How has outlet establishment growth trended over the years?

---

##  Key KPIs Tracked

| KPI | Value |
|---|---|
| 💰 Total Sales | **$1.2 Million** |
| 📦 Total Items Analyzed | **8,523** |
| 📈 Average Sales per Item | **$141** |
| ⭐ Average Customer Rating | **4.0** |

---

##  Key Insights

-  **Supermarket Type 1** dominates with **$787.5K** in total sales — the highest among all outlet types
-  **Tier 3 cities** surprisingly outperform Tier 1 and Tier 2 with **$472.1K** in sales
-  **Fruits & Vegetables** and **Snack Foods** are the top-selling categories at **$178K** and **$175K**
-  **65% of items sold are Low Fat** — showing clear customer health preference
-  Outlets established in **2018** recorded the highest sales at **$204.5K**
-  **Large-sized outlets (High)** account for **42%** of total sales

---

## Dataset Description

**Source:** Kaggle — Blinkit Grocery Dataset  
**Records:** 8,523 rows | **Columns:** 13

| Column | Description |
|---|---|
| Item Identifier | Unique product code |
| Item Type | Product category (16 categories) |
| Item Fat Content | Low Fat / Regular |
| Item Weight | Weight of the product |
| Item Visibility | Shelf visibility score |
| Outlet Identifier | Unique outlet code |
| Outlet Establishment Year | Year outlet was opened (2011–2022) |
| Outlet Size | Small / Medium / High |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 |
| Outlet Type | Supermarket Type 1/2/3 or Grocery Store |
| Sales | Total sales value |
| Rating | Customer rating |

---

## Tools Used

![Microsoft Excel](https://img.shields.io/badge/Microsoft_Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)

- **Pivot Tables** — to summarize sales by outlet, item type, fat content, location
- **Pivot Charts** — bar charts, donut charts, line charts
- **Slicers** — interactive filters for Outlet Size, Outlet Location, Item Type
- **Dashboard Design** — custom colors, KPI cards, layout formatting

---

##  Project Structure

```
blinkit-sales-dashboard/
│
├── README.md
├── BlinkIT_Excel_Dashboard_and_pivots.xlsx
│     ├── Sheet 1: Raw Data         ← 8,523 records
│     ├── Sheet 2: Pivot Sheet      ← All pivot tables & calculations
│     └── Sheet 3: Dashboard        ← Final interactive dashboard
├── BlinkIT_Raw_Data.xlsx
│
└──  visuals/
      └── blinkit_dashboard.png     ← Dashboard screenshot
      └── icons Used.docx           ← Icons in Dashboard
```

---

##  What I Did — Step by Step

1. **Data Understanding** — Explored 13 columns across 8,523 records
2. **Data Cleaning** — Handled inconsistent fat content labels (e.g., "LF" → "Low Fat")
3. **Pivot Tables** — Built 8+ pivot tables for each KPI and chart
4. **Dashboard Design** — Designed a Blinkit-branded dashboard (green & yellow theme)
5. **Slicers Added** — Outlet Size, Outlet Location, Item Type filters for interactivity
6. **Insight Generation** — Identified top-performing outlets, categories, and tiers

---



##  How to Use This File

1. Download the `.xlsx` file
2. Open in **Microsoft Excel** (2016 or later recommended)
3. Go to the **Dashboard** sheet
4. Use the **slicers on the left panel** to filter by:
   - Outlet Size (High / Medium / Small)
   - Outlet Location (Tier 1 / Tier 2 / Tier 3)
   - Item Type (16 categories)
5. All charts update automatically!

---

## Author

**Krishna Priya M** — Data Analyst  

