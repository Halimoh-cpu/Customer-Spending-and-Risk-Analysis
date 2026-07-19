# 💳 Customer Spending and Risk Analysis Dashboard | 2010

> **Data Analysis Portfolio Project**  
> **Researcher:** Olatunji, Halimoh Temidayo  
> **Period Covered:** January 2010 – December 2010  
> **Date Completed:** 2026

---

## 📌 Problem Statement

Financial institutions and retail businesses operating in today's competitive marketplace face a critical challenge, they collect enormous volumes of customer transaction data but frequently lack the analytical clarity to translate that data into actionable business intelligence. Without a clear understanding of who their highest-value customers are, where spending is concentrated, which merchant categories drive the most revenue, how credit risk is distributed across demographic groups, and where potential fraud or anomalous activity exists, businesses are making strategic decisions blindly, leaving revenue opportunities untapped and financial risks undetected.

This project addresses that gap directly. Using customer transaction data covering **2,000 customers** and **1 million transactions** totalling **$45.9 million** across the full 2010 calendar year, this analysis identifies the demographic groups driving the highest spending volumes, uncovers the merchant categories and card types most frequently used, maps credit risk profiles across age groups, detects geographic transaction anomalies that may indicate fraud, and delivers a comprehensive interactive dashboard that empowers business stakeholders to make faster, smarter, and more targeted commercial decisions.

---

## 📊 Dashboard Overview

| KPI | Value |
|-----|-------|
| 💰 Total Spending | **$45.9 Million** |
| 🔁 Total Transactions | **1 Million** |
| 📊 Average Spending | **$43.8** |
| 👥 Total Customers | **2,000** |
| 📅 Period | **January – December 2010** |

---

## 🔑 Key Findings

**Spending by Demographics**
- The **30–49** and **50–59** age groups are joint top spenders at **$19M each** — together accounting for **82.8%** of all customer spending
- **Adults** dominate spending by age status at **$33M (71.9%)**, followed by Youth at **$9M** and Old at **$4M**
- Gender distribution is nearly equal — **Male 50.74%** vs **Female 49.26%**
- The **18–29 age group** records virtually zero spending despite holding a strong average credit score of **711.68** — the largest untapped commercial opportunity in the dataset

**Credit Score Analysis**
- All age groups maintain healthy credit scores consistently **above 700**
- The **90–110** age group holds the highest credit score at **732.71**
- The **70–89** age group holds the lowest at **705.44**
- The narrow 27-point range across all groups confirms uniform credit health across the customer base

**Merchant Category Spending**
- **Wholesale Clubs** is the overwhelmingly dominant spending category — confirming bulk essential purchasing as the primary spending behaviour
- **Service Stations** rank second — reflecting significant fuel and transportation expenditure
- **Utilities, Telecommunications, and Tolls and Bridge Fees** follow — all non-discretionary essential services
- **Package Stores** record the lowest at **$0.11M**

**Card Type Usage**
- **Debit cards dominate at 94.37%** of all transactions
- **Credit cards account for only 5.26%** — representing a significant missed revenue and engagement opportunity
- Debit Premium accounts for the remaining percentage

**Spending Trend**
- Spending remains broadly stable from **January through October**
- A notable **decline toward November** is identified — requiring investigation for seasonal or data coverage causes

**Geographic Anomaly — Fraud Risk**
- **Zurich, Switzerland leads location spending at $3.9K** — significantly ahead of all US-based locations
- **Zion Grove** follows at **$2.8K** and **Zionsville, IN** at **$0.4K**
- The international transaction anomaly in Zurich warrants immediate fraud review

---

<img width="998" height="572" alt="Screenshot 2026-07-19 003833" src="https://github.com/user-attachments/assets/ed24130e-deaa-4391-b38f-3f31ddf86e25" />


## 💡 Recommendations

| # | Recommendation | Priority |
|---|---------------|----------|
| 1 | Target retention and loyalty programmes specifically at the 30–59 age group | 🔴 High |
| 2 | Investigate and flag Zurich, Switzerland transactions for potential fraud | 🔴 High |
| 3 | Develop credit card adoption campaigns targeting high-credit-score customers | 🟡 Medium |
| 4 | Design youth engagement strategy for the 18–29 age group | 🟡 Medium |
| 5 | Explore Wholesale Club partnership or co-branded loyalty programmes | 🟡 Medium |
| 6 | Investigate November spending decline for seasonal or data anomaly causes | 🟢 Low |

---

## 🎨 Colour Psychology Applied

This dashboard uses colour deliberately to communicate financial insight psychologically:

| Colour | Hex | Psychological Message |
|--------|-----|-----------------------|
| Emerald Green | `#059669` | Strong performance — growth and financial health |
| Royal Blue | `#2563EB` | Core stable business — trust and reliability |
| Amber Gold | `#D97706` | Pay attention — valuable but needs monitoring |
| Alert Red | `#DC2626` | Act immediately — fraud risk and anomaly |
| Warning Orange | `#EA580C` | Watch this — declining trend or moderate risk |
| Slate Grey | `#64748B` | Low priority — background context |
| Deep Navy | `#1B2A4A` | Professional financial authority |

> Colour is not decoration — it is communication. Every colour choice in this dashboard is intentional and designed to guide stakeholder attention toward the right insight at the right moment.

---

## 🛠️ Tools Used

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Initial data exploration and structure review |
| **Power Query Editor** | Data cleaning, transformation, column recoding and preparation |
| **Power BI** | Interactive dashboard design, DAX measures, KPI cards, slicers and visual storytelling |

---

## 📁 Repository Structure

```
📦 customer-spending-risk-analysis/
│
├── 📄 README.md                              ← You are here
│
├── 📊 data/
│   ├── raw_customer_data.xlsx                ← Raw transaction dataset
│   └── cleaned_customer_data.xlsx           ← Cleaned and transformed dataset
│
├── 📈 power_bi/
│   └── customer_spending_dashboard.pbix     ← Full interactive Power BI dashboard
│
├── 🖼️ screenshots/
│   ├── dashboard_overview.png               ← Full dashboard screenshot
│   ├── age_group_spending.png               ← Age group chart
│   ├── merchant_categories.png             ← Top merchant categories
│   └── location_anomaly.png               ← Geographic fraud flag
│
└── 📑 presentation/
    └── customer_spending_presentation.pptx  ← Project presentation slides
```

---

## 📋 Dataset Overview

| Feature | Detail |
|---------|--------|
| Total Records | 1,000,000 transactions |
| Total Customers | 2,000 |
| Period | January – December 2010 |
| Total Spending | $45.9 Million |
| Average Transaction | $43.8 |
| Age Groups | 18–29, 30–49, 50–59, 70–89, 90–110 |
| Age Status | Adult, Youth, Old |
| Card Types | Debit, Credit, Debit Premium |
| Filters Available | Use Chip, Merchant State, Card Brand |

---

## 📈 Dashboard Pages and Visuals

| Visual | Type | Insight Delivered |
|--------|------|------------------|
| Total Spending KPI | Card | $45.9M headline figure |
| Total Transactions KPI | Card | 1M transaction volume |
| Average Spending KPI | Card | $43.8 per transaction |
| Total Customers KPI | Card | 2,000 customer base |
| Age Group Spending | Horizontal Bar | 30–59 dominates at 82.8% |
| Credit Score by Age | Column Chart | All groups above 700 |
| Age Status Spending | Bar Chart | Adults lead at $33M |
| Gender Distribution | Pie Chart | Near-equal 50.74% male |
| Top 7 Merchant Categories | Bar Chart | Wholesale Clubs dominant |
| Total Spending Over Time | Area Chart | Stable with November dip |
| Card Type Usage | Donut Chart | Debit dominates at 94.37% |
| Top 7 Locations | Bar Chart | Zurich anomaly flagged |

---

## 🔍 Analytical Focus Areas

```
✅ Customer demographic spending segmentation
✅ Credit score risk profiling by age group
✅ Merchant category revenue concentration analysis
✅ Card type adoption and usage pattern analysis
✅ Geographic transaction anomaly and fraud detection
✅ Time series spending trend analysis
✅ Gender-based spending distribution
✅ Youth customer opportunity gap identification
```

---

## 🏁 Conclusion

This Customer Spending and Risk Analysis Dashboard delivers a comprehensive, data-driven portrait of 2,000 customers across 1 million transactions. The analysis confirms that the **30–59 age group** drives 82.8% of all spending, **Wholesale Clubs** is the dominant merchant category, **Debit cards account for 94.37%** of all transactions, and all customer segments maintain healthy credit scores above 700.

The most actionable findings are the **untapped youth segment** — strong credit scores but zero spending engagement — and the **Zurich, Switzerland international transaction anomaly** which demands immediate fraud investigation. Together, these findings provide a clear and prioritised roadmap for customer retention, credit product development, youth acquisition strategy, and fraud risk management.

---

## 🎓 About This Project

This project is part of my **Data Analysis Portfolio** developed during the:

**Seeding Africa Data Analysis Scholarship Program**  
in partnership with  
**FEMTECH Information Technology Institute**  
*2026*

---

## 📬 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/YOUR-LINKEDIN-URL)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/YOUR-GITHUB-USERNAME)

> 💼 Currently **open to work** — seeking Data Analyst roles, Graduate Trainee programmes, and internship opportunities.

---

## 📄 License

This project is for portfolio and academic demonstration purposes.  
© 2026 Olatunji, Halimoh Temidayo. All rights reserved.

---

*"Data without context is just numbers. Data with the right colour, the right question, and the right analysis becomes a decision."*
