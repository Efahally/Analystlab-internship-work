# 📊 Global Sales Performance Dashboard — Power BI Internship Project

An interactive Power BI dashboard analyzing global order, sales, and profitability data across regions, markets, and product categories. Built as part of a data analytics internship to demonstrate end-to-end BI development — from data modeling to executive-ready reporting.

![Dashboard Preview](assets/dashboard-preview.png)

---

## 🎯 Project Objective

Retail businesses often generate large volumes of transactional data but lack a consolidated view of regional performance. This project consolidates global order-level data into a single interactive dashboard that lets stakeholders quickly identify **which regions and product lines drive sales and profit**, and where performance gaps exist.

## 🗂️ Dataset

The dashboard is built on the **Global Superstore** dataset — order-level retail transaction data including:

| Field Category | Examples |
|---|---|
| Order details | Order ID, Order Date, Ship Date, Ship Mode |
| Geography | Country, Region, Market |
| Customer | Segment |
| Product | Category, Sub-Category |
| Metrics | Sales, Profit, Quantity, Discount |

## 🛠️ Tools & Technologies

- **Power BI Desktop** — data modeling, DAX measures, report design
- **Power Query (M)** — data cleaning and transformation
- **DAX** — calculated measures (Total Orders, Profit Margin, Average Sales)

## ✨ Dashboard Features

- **KPI Cards** — Total Orders, Total Sales, Total Profit, Average Sales, Profit Margin
- **Sales by Region** — clustered column chart comparing regional sales volume
- **Profit by Region** — bar chart highlighting profit contribution by region
- **Average Sales by Region** — line chart tracking average order value across regions
- **Total Orders by Region** — donut chart showing order distribution
- **Sales by Year** — pie chart of yearly sales trends
- **Sales by Market** — column chart comparing performance across global markets
- **Interactive Slicers** — filter the entire report by Category and Segment

## 🔑 Key Insights

- The **Central** region leads across nearly every metric — highest order volume (11K, ~21.7% of all orders), highest sales ($2.8M), and highest profit ($0.31M).
- Profitability doesn't scale purely with order volume — **North Asia** and **North** post strong profit relative to their order counts, while larger regions underperform on margin.
- **Average sale value declines steadily** from ~$390 in Central Asia to ~$150 in EMEA, pointing to differences in pricing or product mix worth further investigation.
- **East, Canada, and the Caribbean** are consistently the lowest contributors across sales, profit, and order volume.

## 🚀 How to Use

1. Clone or download this repository.
2. Open `Global Sals dashboard.pbix` in **Power BI Desktop** (2023 release or later recommended).
3. Use the **Category** and **Segment** slicers to filter the report.
4. Hover over any visual for detailed tooltips, or click a region to cross-filter the entire page.

## 📁 Repository Structure

```
├── Glo_Sales.pbix           # Power BI report file
├── assets/
│   └── dashboard-preview.png # Dashboard screenshot for README preview
└── README.md
```

## 🎓 Skills Demonstrated

- Data modeling and relationship design in Power BI
- DAX measure creation (Profit Margin, Average Sales, Total Orders)
- Dashboard UX and layout design for executive audiences
- Data storytelling — translating raw metrics into business insight

## 📬 Contact

**Longlife Boyefa**
Hallyboy321@gmail.com 

---
*This project was completed as part of a data analytics internship and is intended to showcase Power BI and data visualization skills.*
