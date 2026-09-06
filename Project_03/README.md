# 📦 Inventory Dashboard – Power BI

An interactive Power BI dashboard that tracks retail inventory, sales performance, and stock health across stores, categories, and regions.

## 🔗 Live Dashboard
[View the Power BI Report](https://app.powerbi.com/view?r=eyJrIjoiODhmMDVmMTEtMTdjZC00N2JlLThiZjEtNTczNDJkNjViZjI1IiwidCI6Ijc1ODk4MjEwLWZiNTUtNDk2ZS1iMDEyLWUxYzAzZDEzYWI2MCJ9)

> ⚠️ This is a public share link — anyone with the URL can view the report.

## 📸 Preview

**Overview**
![Dashboard Overview](Dashboard_Page1.png)

**Overview with Filters**
![Dashboard with Filters](Page2.png)

## 📊 Key Metrics (KPI Cards)

| Metric | Description |
|---|---|
| **Total Revenue** | Total sales revenue generated across all stores and products |
| **Inventory Value** | Total monetary value of current stock on hand |
| **Stocks Available** | Total units currently in inventory |
| **DOH (Days of Inventory on Hand)** | Average number of days current stock will last at the current sell-through rate |
| **Inventory Turnover** | Rate at which inventory is sold and replaced over a period (gauge visual) |

## 📈 Visuals

- **Stocks Overview by Month** — Monthly comparison of stocks available vs. total units sold
- **Inventory Value by Category** — Breakdown of inventory value across Furniture, Groceries, Clothing, Toys, and Electronics
- **Total Units Sold by Region** — Units sold across East, South, North, and West regions
- **Detail Table** — Store/Product-level data including Units Sold, Total Revenue, Inventory Level, Inventory Turnover, Sell-through Rate, DOH, and Stock Status

## 🎛️ Filters

The dashboard supports slicing by:
- Year
- Month
- Region
- Store ID
- Category
- Product ID

## 🗂️ Data Source

`retail_store_inventory.csv` — daily-level retail inventory and sales data (~73,000 rows) with the following fields:

| Column | Description |
|---|---|
| Date | Date of record |
| Store ID | Store identifier |
| Product ID | Product identifier |
| Category | Product category (Groceries, Toys, Clothing, Electronics, Furniture) |
| Region | Store region (North, South, East, West) |
| Inventory Level | Units currently in stock |
| Units Sold | Units sold on that date |
| Units Ordered | Units reordered/restocked |
| Demand Forecast | Forecasted demand |
| Price | Unit price |
| Discount | Discount percentage applied |
| Weather Condition | Weather on that date |
| Holiday/Promotion | Flag for holiday or promotion (0/1) |
| Competitor Pricing | Competitor's price for the same product |
| Seasonality | Season label |

## 🛠️ Tools Used

- **Power BI** — data modeling, DAX measures, and dashboard design
- **CSV** — raw data source

## 📁 Repository Structure

```
├── README.md
├── retail_store_inventory.csv
├── Dashboard_Page1.png
├── Page2.png
└── Inventory_Dashboard.pbix   # (add your .pbix file here)
```

## 🚀 How to Use

1. Clone this repository
2. Open `Inventory_Dashboard.pbix` in Power BI Desktop
3. Refresh the data source to point to `retail_store_inventory.csv` (or your live source)
4. Use the slicers at the top to filter by Year, Month, Region, Store, Category, or Product
