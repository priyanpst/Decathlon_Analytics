<div align="center">

# 🏸 Decathlon Sales & Customer Analytics

### Smarter insights. Stronger connections. Better performance.

An end-to-end retail analytics project — from raw transactional data to an executive dashboard — analyzing **30,000 orders**, **8,998 customers**, and **₹36.7 Cr** in sales across Decathlon India (2024–2026).

![Python](https://img.shields.io/badge/Python-3.12-3776AB?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-11557C)
![Excel](https://img.shields.io/badge/Excel-Dashboard-217346?logo=microsoftexcel&logoColor=white)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)

</div>

---

## 📌 Project Overview

This project simulates a real-world **retail business intelligence engagement** for Decathlon India. Starting from a 39-column, 30,000-row transactional dataset, I performed data cleaning, exploratory data analysis, KPI engineering, and customer segmentation in Python, then translated the findings into an interactive **Excel dashboard** for stakeholder consumption.

**Business questions answered:**
- Which sports categories and cities drive the most revenue?
- Are customers returning, and what does retention look like month-to-month?
- How do membership tier, sales channel, and demographics affect spend?
- Where are the margin and operations risks (returns, delivery, discounting)?

---

## 🖥️ Dashboard Preview

<img src="assets/dashboard_preview.png" alt="Decathlon Sales & Customer Analytics Dashboard" width="100%">

*Interactive Excel dashboard with year-slicers (2024 / 2025 / 2026), KPI cards, top-5 sport types, and channel/segment breakdowns.*

---

## 🗂️ Dataset

| Attribute | Detail |
|---|---|
| Source | Synthetic Decathlon India transactions dataset |
| Records | 30,000 orders \| 8,998 unique customers |
| Time span | Jan 2024 – Dec 2026 |
| Columns | 39 fields — order, customer, product, store, delivery, promotion, and financial attributes |
| Geography | 12 cities across 11 states |
| Stores | 5 physical stores + Website + Mobile App |
| Data quality | 0 missing values across all 39 columns |

<details>
<summary><strong>Full column list</strong></summary>

`Order_ID` · `Order_Date` · `Order_Time` · `Customer_ID` · `Customer_Name` · `Gender` · `Age` · `Age_Group` · `City` · `State` · `Membership_Type` · `Customer_Segment` · `Product_ID` · `Product_Name` · `Product_Category` · `Brand` · `Sport_Type` · `Quantity` · `Unit_Price` · `Discount_Percent` · `Discount_Amount` · `Sales_Amount` · `Final_Amount` · `Cost_Price` · `Profit` · `Store_ID` · `Store_Name` · `Sales_Channel` · `Payment_Method` · `Salesperson` · `Delivery_Type` · `Delivery_Days` · `Customer_Rating` · `Return_Status` · `Return_Reason` · `Promotion_Campaign` · `Quarter` · `Month` · `Year`

</details>

---

## 🧰 Tech Stack

| Layer | Tools |
|---|---|
| Data wrangling & EDA | Python, Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Dashboard / BI layer | Excel (pivot-driven, slicer-based) |
| Version control | Git & GitHub |

---

## 🔑 Headline KPIs

| Metric | Value | YoY |
|---|---:|:---:|
| **Total Sales** | ₹36.7 Cr | ▲ 40.8% |
| **Total Orders** | 30,000 | ▲ 40.1% |
| **Total Customers** | 8,998 | ▲ 13.5% |
| **Average Order Value** | ₹12,236 | ▲ 0.5% |
| **Gross Profit** | ₹11.27 Cr | — |
| **Gross Margin** | 30.7% | — |
| **Customer Retention Rate** | 64.6% | — |
| **Return Rate** | 8.1% | — |
| **Average Customer Rating** | 3.0 / 5 | — |

---

## 📊 Visual Insights

### 1. Monthly Sales Trend
<img src="assets/sales_trend.png" width="100%">

- Sales scaled sharply from **₹12.9 Cr (2024)** to **₹13.1 Cr (2025)**, with 2026 tracking at **₹10.6 Cr** through the available months.
- Order volume growth (+40.1%) closely tracks revenue growth (+40.8%), showing growth is **volume-led rather than price-led** — AOV moved just +0.5% YoY.

### 2. Sales by Product Category
<img src="assets/category_donut.png" width="100%">

- **Cycling is the single largest category**, generating **₹8.1 Cr (~22% of total sales)** — more than double the next closest category.
- The remaining nine categories (Camping, Running, Fitness, Trekking, Cricket, Badminton, Football, Yoga, Swimming) are tightly clustered between **₹2.6 Cr and ₹4.1 Cr**, indicating a well-diversified — but Cycling-dependent — portfolio.

### 3. Top 5 Sport Types
<img src="assets/top_sports.png" width="100%">

- Cycling leads decisively; **Outdoor, Running, Gym, and Hiking** round out the top 5 within a narrow ₹3.0–4.1 Cr band.
- Despite the revenue gap, **order counts across all top categories are nearly identical (~2,850–3,150 orders each)** — Cycling's lead comes from **higher basket value per order**, not more transactions.

### 4. Customer Segment & Sales Channel
<img src="assets/segment_channel.png" width="100%">

- **Returning customers contribute ₹16.5 Cr (~45% of revenue)** from 13,468 orders — the single most valuable segment, ahead of Loyal (₹11.1 Cr) and New (₹9.1 Cr).
- Revenue is **evenly split across all three sales channels** — Website (₹12.3 Cr), Store (₹12.2 Cr), and Mobile App (₹12.2 Cr) — confirming a mature omnichannel strategy with no single point of failure.

### 5. Top 10 States by Sales
<img src="assets/top_states.png" width="100%">

- **Maharashtra leads with ₹6.1 Cr** (almost double any other state), driven by Mumbai + Pune combined.
- Uttar Pradesh, Tamil Nadu, Gujarat, Rajasthan, and Haryana form a closely matched second tier (₹3.1–3.2 Cr each), reflecting balanced expansion across India's metro markets.

### 6. Retention & Returns
<img src="assets/retention_returns.png" width="100%">

- **64.6% of customers are repeat buyers** — a strong signal of product-market fit for a sporting-goods retailer — with monthly retention holding steady between 10–17% (no seasonal collapse).
- **91.9% of orders are kept (not returned)**, and returns hold at a manageable **8.1%**, well within typical retail benchmarks.

### 7. Age Group & Gender Split
<img src="assets/age_gender.png" width="100%">

- Customer base is **almost perfectly gender-balanced (50% / 50%)** — a rarity in sporting goods retail, suggesting Decathlon's assortment resonates equally across genders.
- **Adults (25–54) drive ~70% of revenue**, with Seniors and Teens contributing smaller but meaningful shares (17.5% and 12.6% respectively) — supporting cross-generational marketing.

### 8. Correlation Matrix — Numeric Features
<img src="assets/correlation.png" width="100%">

- **Profit correlates almost perfectly with Final Amount (r = 0.95)**, confirming margins are stable — Decathlon is not sacrificing profitability to drive volume.
- **Discount depth has virtually no relationship with order value (r = -0.08) or customer rating (r ≈ 0)** — promotions are not the primary revenue lever, and satisfaction is unaffected by how much a customer saved.
- **Delivery speed shows no measurable link to customer rating (r = -0.01)** — implying rating drivers lie elsewhere (product, service, in-store experience).

---

## 💡 Key Business Insights

1. **Cycling is the crown-jewel category** — it out-earns every other category by 2x+ and should anchor inventory planning and marketing spend.
2. **Growth is coming from customer acquisition and repeat purchases, not price increases** — order volume (+40%) and customer count (+13.5%) are outpacing AOV (+0.5%).
3. **Returning customers are the most profitable segment** — retention programs targeting this cohort will have outsized ROI versus new-customer acquisition.
4. **Omnichannel is genuinely balanced** — Website, Store, and App each contribute ~33% of revenue, so channel-specific disruption carries limited business risk.
5. **Discounting isn't moving the needle** — with near-zero correlation to order value or satisfaction, promo spend may be better redirected toward loyalty or category expansion.
6. **Geographic concentration risk in Maharashtra** — it's the top state by a wide margin; a regional slowdown there would disproportionately affect national numbers.

---

## 🎯 Recommendations

- **Double down on Cycling** with expanded SKUs, bundle offers, and dedicated campaigns — it is the highest-value category by a clear margin.
- **Invest in retention over acquisition**: loyalty perks, personalized re-engagement, and post-purchase service for the "Returning" segment (already 45% of revenue).
- **Audit promotional ROI** — given near-zero correlation between discount depth and order value/rating, test reducing blanket discounts in favor of targeted, segment-specific offers.
- **De-risk geographic concentration** by accelerating growth in the second-tier states (UP, TN, Gujarat, Rajasthan, Haryana) that are already performing at ~50% of Maharashtra's level.
- **Investigate the driver of the 3.0/5 average rating** — since discounting and delivery speed show no correlation with satisfaction, root cause is likely product experience or in-store service quality and merits a dedicated CSAT deep-dive.

---

## ⚙️ How to Reproduce

```bash
git clone https://github.com/<your-username>/decathlon-sales-analytics.git
cd decathlon-sales-analytics
pip install -r requirements.txt

python scripts/analysis.py --input data/Decathlon_Synthetic_Data_30000.xlsx --outdir assets/
```

---

## 📁 Repository Structure

```
decathlon-sales-analytics/
├── assets/                     # Dashboard preview + all generated charts
├── data/                       # Source dataset (30,000-row synthetic transactions)
├── scripts/
│   └── analysis.py             # End-to-end EDA + chart generation script
├── requirements.txt
└── README.md
```

---

## 👤 Author

**[Your Name]**
Data Analyst | Python · SQL · Excel · Power BI
📧 your.email@example.com · 🔗 [LinkedIn](https://linkedin.com/in/your-profile) · 💻 [Portfolio](https://your-portfolio.com)

> ⭐ If you found this project useful or interesting, consider giving it a star!

---

<sub>*Note: This project uses a synthetically generated dataset built to mirror the structure and scale of real Decathlon retail transactions, for portfolio and demonstration purposes.*</sub>
