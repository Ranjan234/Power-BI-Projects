# ☕ Coffee Shop Sales Dashboard

An interactive Power BI dashboard that shows **when customers buy, what they buy and how they pay** in a coffee shop.

![Coffee Sales Dashboard](https://github.com/Ranjan234/Power-BI-Projects/blob/main/Project_06/Files/Data/Screenshot%202026-10-25%20144757.png)

## Business questions
1. How do sales change from month to month?
2. Which drinks sell the most?
3. At what time of day do customers buy?
4. How do customers pay, and does it change how much they spend?

## Dashboard at a glance
| Measure | Value (all data) |
|---|---|
| Total sales | 115.43K [add currency] |
| Total transactions | 3,636 |
| Average sale per transaction | 31.75 |

**Filters:** Cash Type (card / cash) and Year. **Clear all** resets them.

![Filtered view: card payments, 2024](https://github.com/Ranjan234/Power-BI-Projects/blob/main/Project_06/Files/Data/Screenshot%202026-10-25%20144815.png)

## Key insights
- **Two drinks make almost half of the sales.** Latte (27.87K, 24%) and Americano with Milk (25.27K, 22%). With Cappuccino, the top three reach about 62%. Espresso is the smallest at 2.81K (2.4%).
- **Sales are spread evenly through the day.** Morning 32.4%, afternoon 33.8%, night 33.8%.
- **Sales peak in October.** In the 2024 view, sales are low from March to July, rise from August, and peak in October at about double the spring level.
- **More customers, not bigger spending.** The average sale stays at about 31.7 in every filter. Revenue grows when transactions grow.
- **Almost everyone pays by card.** Cash is about 2.8% of sales (89 of 3,636 transactions). Cash customers spend a little more per visit (about 35.7 against 31.7), but the sample is too small to be sure.

## Recommendations
1. **Prepare for the autumn peak.** Plan staff, milk and cups before September and October.
2. **Lift the slow months (March to July).** Test iced drinks, a loyalty card or a happy-hour offer, and measure the result.
3. **Never run out of the top three drinks.** Latte, Americano with Milk and Cappuccino bring about 62% of sales.
4. **Grow the average sale.** Try add-ons, size upgrades or a drink and snack combo.

## Data
- **Source:** [add dataset link or "sample dataset"]
- **Period:** [add start date] to [add end date]
- **Size:** 3,636 transactions
- **Main fields:** date, time of day, payment type (card or cash), coffee name, sales amount *(check against your file)*

## What I did
- Cleaned and prepared the data
- Created measures: Total Sales, Total Transactions, Average Sale (sales ÷ transactions)
- Built a monthly trend chart, a time-of-day chart and a product ranking
- Added slicers (Cash Type, Year) and a Clear all button
- Designed a coffee-themed dashboard layout

## Tools
Power BI (DAX, slicers, line, donut and bar charts)

## Limitations
- **Small dataset.** One busy week can change the charts.
- **The monthly trend adds the same month from different years.** Use the Year filter to see one year at a time.
- **No cost data,** so this dashboard shows sales, not profit.
- **Only 89 cash transactions,** so cash results are not reliable.
- **Product mix in early 2025** looks different from 2024 (for example more Americano and Cocoa, less Latte). Only a few months are available, so this needs more data.

## Repository structure
```
├── README.md
├── images/
│   ├── dashboard-overview.png
│   └── dashboard-filtered-card-2024.png
├── data/
│   └── [add data file]
└── [add .pbix file]
```

## 🔗 Project Links

- **GitHub Repository:** [GitHub Repository](https://github.com/Ranjan234/Power-BI-Projects/tree/main/Project_06)
- **Power BI Dashboard:** [Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiNTVlNzA4OTktM2E5Ni00Mjk4LWE1M2MtNGEwYTdlNTI1YjcyIiwidCI6Ijc1ODk4MjEwLWZiNTUtNDk2ZS1iMDEyLWUxYzAzZDEzYWI2MCJ9)

## Author
**Soumya Ranjan Sahoo** · Data Analyst
[LinkedIn](https://www.linkedin.com/in/soumyaranjansahoo0/) · [GitHub](https://github.com/Ranjan234)
