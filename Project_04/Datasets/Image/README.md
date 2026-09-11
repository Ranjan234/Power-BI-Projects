# 🦷 Clinic Performance Analysis — Power BI Dashboard

An interactive Power BI dashboard analyzing revenue, profitability, and operational efficiency across multiple clinic locations. Built to help stakeholders track KPIs, identify underperforming locations/services, and monitor patient retention trends.

![Dashboard Overview](Project_04/Datasets/Image/Screenshot 2026-09-11 203013.png)

---

## 📌 Project Overview

This project analyzes clinic operations data across **5 locations** (New York, Los Angeles, Miami, Chicago, Houston) to answer key business questions:

- Which locations and treatment types drive the most revenue and profit?
- How efficient are clinic operations (wait times, no-show rates)?
- How does performance trend year-over-year?
- Where are the biggest opportunities for cost optimization or growth?

The report is fully interactive with slicers for **Location**, **Treatment Type**, and **Year**, allowing stakeholders to drill into any segment of the business.

---

## 📊 Key Metrics (KPIs)

| Metric | Value (All Years) |
|---|---|
| Total Revenue | $937.6K |
| Total Profit | $192.365K |
| Profit Margin | 20.5% |
| Avg Wait Time | 21.20 min |
| No-Show Rate | 15.5% |
| Revenue Per Patient | $469 |

---

## 🔍 Key Insights

- **YoY Growth:** Revenue per patient increased ~21% from 2024 ($425) to 2025 ($513), with profit margin improving from 19.9% to 21.0%.
- **Operational improvement:** No-show rate dropped from 16.7% (2024) to 14.3% (2025).
- **Top performer:** New York consistently leads in revenue, revenue per patient (up to $595), and appointment volume.
- **Underperformer:** Houston shows the lowest revenue per patient (as low as $252–$298) and smallest patient volume — a candidate for growth strategy or review.
- **Treatment-level insight:** Cleaning appointments (2024) show the longest average wait time (24.73 min) and a lower profit margin (16.2%) compared to the overall average — a potential process bottleneck.
- **Patient retention:** Returning patients outnumber new patients at every location, indicating strong retention but an opportunity to invest in new-patient acquisition.
- **Seasonality:** Appointment volume dips in Jan–Feb and peaks around August, useful for staffing and marketing planning.

---

## 🖼️ Dashboard Views

| All Data | 2024 | 2025 | Filtered: Cleaning (2024) |
|---|---|---|---|
| ![All](./screenshots/all.png) | ![2024](./screenshots/2024.png) | ![2025](./screenshots/2025.png) | ![Cleaning](./screenshots/cleaning.png) |

---

## 🛠️ Tools & Techniques

- **Power BI Desktop** — data modeling, report design, interactivity
- **DAX** — custom measures including:
  - Total Revenue, Total Profit, Profit Margin %
  - Revenue Per Patient
  - No-Show Rate %
  - Average Wait Time
- **Data Visualization** — KPI cards, bar/column charts, stacked bar charts, line/area charts, cross-filtering slicers

---

## 📁 Repository Contents

```
├── Clinic_Performance_Analysis.pbix   # Power BI report file
├── screenshots/                       # Dashboard preview images
└── README.md                          # Project documentation
```

---

## ▶️ How to Use

1. Download `Clinic_Performance_Analysis.pbix`
2. Open it in **Power BI Desktop** (free download from Microsoft)
3. Use the slicers (Location, Treatment Type, Year) to explore the data interactively

---

## 📬 Connect

If you found this project useful or have feedback, feel free to connect with me on [LinkedIn](#) or open an issue in this repo.
