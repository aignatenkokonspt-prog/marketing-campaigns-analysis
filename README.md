# marketing-campaigns-analysis

## Dashboard Preview

![Marketing Campaigns - Overview](Marketing_campaigns_screen1.png)

![Marketing Campaigns - Payback & Cohorts](Marketing_campaigns_screen2.png)

🔗 **[View Interactive Dashboard in Redash](https://redash.public.karpov.courses/dashboards/10971-marketing_campaigns)

## Campaign Comparison Matrix

| Metric | Campaign 1 (YouTube) | Campaign 2 (Targeted Ads) | Comment |
| :--- | :---: | :---: | :--- |
| **New users** | 171 | **236** | Campaign 2 brought more initial volume |
| **CAC** | 1,462 RUB | **1,068 RUB** | Campaign 2 was cheaper to acquire |
| **ROI** | **+14.50%** | -1.61% | **Campaign 1** generated profit (1.145 RUB per 1 RUB spent) |
| **AOV** | 371.73 RUB | 380.88 RUB | Equal average order value (~375 RUB) |
| **Day 7 Retention** | **22%** | 9% | **Campaign 1** brought higher quality, loyal users |
| **Payback Period** | **Day 5** | Not achieved (7+ days) | **Campaign 1** broke even within the first week |

---

### Key Takeaways by Dashboard Widgets

### 1. Acquisition & Unit Economics (CAC & ROI)
* **CAC vs Quality:** Campaign 2 had a lower initial CAC (1,068 RUB vs 1,462 RUB), but brought lower-quality traffic.
* **ROI Performance:** Campaign 1 achieved a positive ROI of **+14.50%**, while Campaign 2 remained unprofitable at **-1.61%**.

**[Acquisition & Unit Economics](./sql/01_acquisition_unit_economics.sql)** — CAC, ROI, and core performance metrics for both campaigns.

### 2. Monetization & User Quality (AOV & Retention)
* **Average Order Value:** AOV is nearly identical across both campaigns (~375 RUB).
* **Retention Driver:** Campaign 1 retention on Day 7 is **22%** compared to only **9%** in Campaign 2. Higher order frequency drove the profit, not higher prices.

### 3. Payback Period (Cumulative ARPPU vs CAC)
* **Break-even Point:** Cumulative ARPPU for Campaign 1 crossed the CAC line on **Day 5**.
* **Unprofitable Cohort:** Campaign 2 failed to cover its CAC within the 7-day tracking window.

---

## Executive Summary & Recommendation

* **Final Verdict:** Despite higher initial signups in Campaign 2, **Campaign 1 was significantly more successful** due to strong retention and fast payback.
* **Business Action:** Stop funding Campaign 2 (Targeted Ads) and scale Campaign 1 (YouTube Influencers) for future marketing budget allocation.

