# 🛒 Online Store Sales Dashboard — Power BI

A comprehensive **Power BI sales analytics dashboard** built to monitor and analyze the performance of an online retail store. The report provides end-to-end visibility into revenue trends, order fulfillment, customer behavior, and product performance — all in a single interactive page.

---

## 📊 Dashboard Overview

The report contains **1 interactive page** with **9 visualizations** covering the following key business areas:

| Visual Type | Metric Analyzed |
|---|---|
| 📈 Stacked Area Chart | Monthly Revenue Trend |
| 🍩 Donut Chart | Order Status Breakdown |
| 📊 Column Chart | Revenue by Product |
| 📉 Bar Chart | Revenue by Referral Source |
| 🥧 Pie Chart | Orders by Payment Method |
| 📊 Clustered Column Chart | Yearly Revenue Comparison |
| 📊 Clustered Column Chart | Unique Customers by Year |
| 📊 Clustered Column Chart | Total Orders by Year |

---

## 🔍 Key Metrics Tracked

- **Total Revenue** — overall and broken down by product, referral source, and year
- **Total Orders** — volume trends and order status (fulfilled, pending, cancelled, etc.)
- **Unique Customers** — year-over-year customer growth
- **Payment Methods** — distribution of how customers pay
- **Referral Sources** — which channels drive the most revenue
- **Monthly Trends** — seasonality and revenue fluctuations over time

---

## 🗂️ Data Model

The report is built on two core tables:

- **`Sheet1`** — transactional sales data including `Product`, `Total Revenue`, `Total Orders`, `OrderStatus`, `ReferralSource`, `PaymentMethod`, `Unique Customers`
- **`DateTable`** — a dedicated date/calendar table supporting time intelligence (month, year hierarchy)

---

## 🚀 How to View

### Option 1 — Live Interactive Report *(Recommended)*
> 🔗 **[View Live Dashboard →](#)** *(replace `#` with your Power BI publish-to-web link)*

### Option 2 — Open Locally
1. Download [`OnlineStoreSales.pbix`](./OnlineStoreSales.pbix)
2. Open with [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free)

---

## 🛠️ Built With

- [Power BI Desktop](https://powerbi.microsoft.com/desktop/) — 2026.04
- DAX for calculated measures and time intelligence
- Custom Date Table for year/month-level filtering

---

## 📁 Repository Structure

```
📦 OnlineStoreSales
 ┣ 📊 OnlineStoreSales.pbix    ← Power BI report file
 ┣ 📸 screenshots/              ← Preview images (optional)
 ┗ 📄 README.md
```

---

## 🙋 Author

> Made with 💙 using Power BI  
> Feel free to fork, explore, or reach out with feedback!
