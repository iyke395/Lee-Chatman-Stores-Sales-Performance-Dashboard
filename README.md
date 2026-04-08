# Lee Chatman Stores — Sales Performance Dashboard

> A 3-page dark theme Power BI dashboard analyzing sales, merchandise performance, and customer behaviour across local and international markets.

---

## Dashboard Preview

### Page 1 — Sales Overview
![Sales Overview](images/page1_sales_overview.png)

### Page 2 — Merch Performance
![Merch Performance](images/page2_merch_performance.png)



---

## Business Context

Lee Chatman Stores operates across local and international markets, selling across three product categories: Clothing, Ornaments, and Other. The business needed a centralized view of its sales performance — one that a non-technical stakeholder could navigate without needing filtered exports or manual reporting.

The dashboard covers **November 2023 to November 2024**, tracking revenue, orders, shipping, product performance, customer ratings, and buyer demographics — all in one interactive report.

---

## Dashboard Pages

### Page 1 — Sales Overview

The entry page gives an at-a-glance view of the overall business health.

**KPI Cards (top row)**
| Metric | Value |
|---|---|
| Total Sales | $856.46K |
| Total Qty Sold | 12.33K |
| Total Orders | 7.39K |
| Total Shipping | $108.20K |
| Average Rating | 3.50 / 5 |

Each KPI card includes a sparkline trend, a breakdown sub-metric, and a Month selector for period-specific filtering.

**Local vs International Sales**
- Local Sales: $470K (45.17%)
- International Sales: $387K (54.83%)

International sales lead slightly, making global market retention a priority for the business.

**Sales Trend — Year & Month**

A dual-line area chart plots Local and International sales from Nov 2023 to Nov 2024. Sales peaked around mid-2024 before declining in Q4. The chart includes toggle buttons to isolate either market.

**Sales by Age Range**

The 18–24 age group is the largest buyer segment across both local and international markets, followed by 30–35 and 25–29. Younger audiences drive the majority of volume.

**Sales by Product Category**

Clothing dominates across both markets. Ornaments and Other categories contribute but at significantly lower volumes. This gap is consistent across local and international splits.

**Location Analysis Table**

A ranked table of order locations with Total Orders, Total Qty Sold, Total Sales, MoM Growth, and a sparkline for monthly trend per city.

| Rank | Location | Total Sales |
|---|---|---|
| 1 | Sydney | $48,049 |
| 2 | San Francisco | $41,321 |
| 3 | New Jersey | $39,889 |
| 4 | Mumbai | $38,115 |
| 5 | Sacramento | $37,756 |

25+ cities are tracked. A location search bar at the top of the dashboard allows instant filtering by city.

---

### Page 2 — Merch Performance

This page focuses on product-level and gender-based analysis.

**Measure Parameter Switcher**

A custom parameter at the top of the page lets users switch the entire page analysis between three measures — Total Sales, Total Qty Sold, and Total Orders. Every visual on the page responds to the selection simultaneously.

**Sales by Buyer Gender**

| Gender | Total Orders | Total Sales | Star Rating |
|---|---|---|---|
| Male | 5,190 (70.09%) | $600,329 | ★★★★☆ |
| Female | 2,210 (29.91%) | $256,133 | ★★★☆☆ |

Male buyers account for the majority of both orders and revenue. Female buyers rate products slightly lower on average.

**Sales by Product ID**

A horizontal bar chart ranks top products by revenue. Top 5:

| Product | Revenue |
|---|---|
| BF1548 | $191K |
| BF1543 | $144K |
| BF1550 | $140K |
| BF1549 | $89K |
| BF1546 | $74K |

BF1548 outperforms the second product by $47K — a significant gap worth investigating for stock and marketing focus.

**Shipping by Year, Month & Product Category**

A grouped bar chart tracks monthly shipping costs split by Clothing, Ornaments, and Other. Shipping peaked in May 2024. Clothing consistently leads shipping volume across all months. Average shipping cost per order: **$14.63**.

**Rating Analysis**

- Average Rating: 3.50 / 5
- Clothing leads in Total Sales by product category
- 4-star and 5-star reviews are the most frequent
- 1-star reviews exist but are a smaller portion of the total

**Compliant Analysis Table**

A table maps real customer review text to star ratings and total orders. Negative reviews flag delivery delays, product quality, and mismatch between expectation and delivery. Positive reviews mention fast delivery, craftsmanship, and competitive pricing.

---

**Page Summary Tooltip**

Hovering over a designated area opens a full-page tooltip panel that auto-summarises the entire page:

- **Revenue Split:** $856.5K total — Males 70.1% ($600.3K) vs Females 29.9% ($256.1K)
- **Top Product:** BF1548 at $191K, followed by BF1543 ($144K) and BF1550 ($140K)
- **Shipping Trend:** Peaked May 2024. Clothing leads volume consistently.
- **Customer Ratings:** Average 3.50/5. Most reviews fall in the 4–5 star range.
- **Sentiment:** Positive reviews mention fast delivery, quality craftsmanship, and pricing. Delivery delays flagged in lower-rated reviews.

---

## Key Business Insights

1. **International sales lead domestic** — at 54.83% of total revenue, international market retention deserves as much attention as local acquisition.

2. **BF1548 is the clear hero product** — at $191K it outsells the second product by nearly $50K. Inventory and marketing should reflect this.

3. **18–24 is the dominant buyer segment** — across both markets. Campaigns and product design should skew toward this group.

4. **Male buyers drive 70% of revenue** — but female buyers leave lower ratings. There may be a product-expectation gap worth investigating.

5. **Clothing dominates across all metrics** — Ornaments and Other are significantly behind. Expanding or promoting secondary categories could diversify revenue.

6. **Q4 sales decline is visible** — sales drop noticeably from October into November 2024. Whether this is seasonal or structural needs further investigation.

7. **Delivery experience is a recurring complaint** — low-rated reviews consistently mention delays. Shipping process improvement could directly improve the average rating above 3.50.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Power BI Desktop | Dashboard development |
| DAX | Measures, KPIs, dynamic calculations |
| Power Query | Data transformation and modelling |
| HTML Visuals | Custom styled summary cards |
| AI Scripting | HTML visual prompt generation |

---

## About

Built by **Emmanuel** — Master Data Lead & BI Analyst.  
Teaching data analytics at **Iyke Analytics**.

---
