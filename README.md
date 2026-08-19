# Decathlon Sales & Customer Analytics

A data analysis project built on a 30,000-row synthetic Decathlon sales dataset (FY2024–FY2026), covering an executive Power BI–style dashboard and a full written analytics report answering 15 real business questions with data.



## 📊 Project Overview

This project simulates a real-world retail analytics workflow:

- **Source data** → 30,000 synthetic orders across 8,998 customers, 39 fields (product, customer, store, channel, payment, delivery, returns, etc.)
- **Dashboard** → Executive KPI dashboard (Total Sales, Orders, Customers, AOV, Top 5 Sports, Sales Trend, Category Split, Retention, Gender Split)
- **Report** → A 13-page PDF report that validates the dashboard numbers and goes deeper with structured Q&A across Sales, Customers, and Operations

## 🗂️ Repository Contents

| File | Description |
|---|---|
| `Decathlon_Synthetic_Data_30000.xlsx` | Raw dataset — 30,000 orders, 39 columns |
| `Decathlon_Dashboard_Landscape.png` | Executive KPI dashboard |
| `Decathlon_Analytics_Report.pdf` | Full written analytics report (15 business questions, charts, recommendations) |

## 🔑 Key Metrics

| Metric | Value |
|---|---|
| Total Sales | ₹36.7 Cr |
| Total Orders | 30,000 |
| Total Customers | 8,998 |
| Average Order Value | ₹12,236 |
| Total Profit | ₹11.27 Cr (30.7% margin) |
| Customer Retention | 64.6% |
| Return Rate | 8.05% |
| Average Customer Rating | 3.00 / 5 |

## 📈 Dataset Fields

Order details, customer demographics (age, gender, city, state, membership tier, segment), product info (category, sport type, brand), pricing (unit price, discount, final amount, cost, profit), fulfilment (channel, delivery type, delivery days, store, salesperson), and post-sale data (rating, return status, return reason, promotion campaign).

## ❓ Business Questions Answered

**Sales & Product**
1. Which sport category generates the most revenue?
2. How is revenue distributed across product categories, and which are most profitable?
3. Is there seasonality in sales?
4. Which promotional campaigns drive the most sales?
5. How does discounting affect profitability per order?

**Customer**
6. What is the customer retention rate?
7. How is revenue split between male and female customers?
8. Which customer segments and membership tiers contribute the most revenue?
9. Which age group is most valuable?
10. Which cities and states are the strongest markets?

**Operations**
11. Which sales channel performs best — Website, Store, or Mobile App?
12. What is the order return rate, and why are customers returning products?
13. Which payment method is most popular?
14. Does delivery type affect customer satisfaction?
15. Are sales concentrated in a few stores, or evenly spread?

Full answers, supporting charts, and figures are in [`Decathlon_Analytics_Report.pdf`](./Decathlon_Analytics_Report.pdf).

## 💡 Key Findings

- **Cycling** is the single most important category — 22% of both sales and profit.
- Retention is strong (64.6% repeat buyers), but the flat ~3.0/5 average rating suggests a satisfaction ceiling worth investigating.
- Discounts beyond ~25% materially erode per-order profit — roughly halved at the 40% discount tier.
- Fulfilment issues (wrong item delivered, late delivery) drive nearly 40% of all returns — an operational fix, not a demand problem.
- Channel mix (Website / Store / Mobile App) and payment mix (Wallet / Cash / UPI / Card) are both well balanced — no concentration risk.

## 🛠️ Tools Used

- **Microsoft Excel** — data cleaning, pivot tables, formulas (SUMIFS, COUNTIFS, AVERAGEIFS), and all aggregations behind the KPIs and charts
- **Excel PivotCharts / Dashboard** — the executive KPI dashboard
- PDF export/report compiled from the Excel analysis

## 📁 How This Was Built

1. Raw transaction data (30,000 rows, 39 columns) cleaned and structured in the `DATA` sheet
2. Pivot tables built per business question (sport type, category, gender, segment, channel, payment method, returns, etc.)
3. KPIs (Total Sales, Orders, Customers, AOV, Retention, Margin) calculated with Excel formulas in the `INSIGHTS` sheet
4. Dashboard assembled using Excel charts, cards, and slicers (Year filter)
5. Findings written up and exported as a PDF report

## 📄 License

Synthetic dataset created for portfolio/demonstration purposes only. Not real Decathlon business data.

---

**Author:** *[Your Name]*
📧 *[your.email@example.com]* · 🔗 [LinkedIn](#) · 💻 [Portfolio](#)
