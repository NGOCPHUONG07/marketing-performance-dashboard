# Marketing Performance Dashboard | Power BI

An interactive Power BI dashboard developed to monitor marketing performance across advertising channels and campaigns. The dashboard provides business insights into customer acquisition, campaign effectiveness, advertising efficiency, and revenue performance to support marketing decision-making.

---

# Dashboard Preview

## Executive Dashboard

<img width="632" height="356" alt="image" src="https://github.com/user-attachments/assets/d674109e-41ec-4400-b4f5-0a7f2632053f" />


## Detailed Analysis Dashboard

<img width="692" height="390" alt="image" src="https://github.com/user-attachments/assets/456399c9-9556-468b-ac08-03c816d512cd" />


---

# 🎯 Business Objectives

This dashboard aims to answer the following business questions:

- Which advertising channels generate the highest revenue?
- Which marketing campaigns achieve the best ROAS?
- How efficiently are customers converted through the marketing funnel?
- How do advertising costs compare with generated revenue?
- Which campaigns have the lowest acquisition cost?
- How does marketing performance change over time?

---

# Key KPIs

The dashboard tracks six important marketing KPIs:

| KPI | Description |
|------|-------------|
| **Total Revenue** | Total revenue generated from all campaigns |
| **Total Advertising Spend** | Total marketing investment |
| **Leads** | Number of leads generated |
| **Conversions** | Number of successful conversions |
| **ROAS** | Return On Advertising Spend |
| **CPA** | Cost Per Acquisition |
| **CPL** | Cost Per Lead |
| **CPC** | Cost Per Click |

---

# Dashboard Features

## Executive Dashboard

Provides a high-level overview of marketing performance.

### Highlights

- KPI Cards
    - Total Revenue
    - Advertising Spend
    - Leads
    - Conversions
    - ROAS

- Revenue Trend Analysis
    - Revenue over time
    - Quarterly and monthly comparison

- Revenue by Campaign
    - Compare campaign contribution

- Orders by Advertising Channel

- ROAS by Channel

- Revenue vs Advertising Spend Trend

---

## Detailed Dashboard

Focuses on campaign efficiency and customer acquisition performance.

### Highlights

- Marketing Funnel
    - Impressions
    - Clicks
    - Leads
    - Conversions

- Conversion Rate Analysis
    - Impression → Click
    - Click → Lead
    - Lead → Conversion

- Channel Performance
    - Revenue
    - Advertising Spend
    - ROAS
    - CPA

- Campaign Performance
    - Revenue
    - Spend
    - ROAS
    - CPA

---

# Key Business Insights

- Email marketing generated the highest ROAS, making it the most cost-effective advertising channel.

- Baseline Campaign produced the highest total revenue among all campaigns.

- Revenue generally increased throughout the analysis period, although advertising spend fluctuated significantly across months.

- Marketing funnel analysis reveals a considerable drop-off between impressions and conversions, highlighting opportunities to optimize customer acquisition.

- Campaign performance varies substantially, suggesting that marketing budget allocation should prioritize high-ROAS campaigns.

---

# Tools & Technologies

- Microsoft Power BI
- Power Query
- DAX (Data Analysis Expressions)
- Data Modeling
- Interactive Filters & Slicers

---

# Data Model

The dashboard is built using a star-schema-inspired data model.

Main entities include:

- Marketing Campaigns
- Advertising Channels
- Calendar Table
- Marketing Metrics

Relationships were optimized to support accurate filtering and efficient DAX calculations.

---

# DAX Measures

Examples of calculated measures include:

- Total Revenue
- Total Spend
- ROAS
- CPA
- CPC
- CPL
- Conversion Rate
- Total Leads
- Total Conversions

---

# Dashboard Features

- Interactive slicers
- Cross-filtering visuals
- Drill-down by Year → Quarter → Month
- Campaign comparison
- Channel comparison
- Responsive KPI cards
- Clean executive-style layout

---

# Repository Structure

```
Marketing-Performance-Dashboard/
│
├── README.md
├── Marketing_Performance_Dashboard.pbix
├── dashboard1.png
├── dashboard2.png
└── assets/
```

---

# Skills Demonstrated

- Power BI Dashboard Development
- Data Modeling
- DAX Calculations
- Power Query
- Marketing Analytics
- KPI Design
- Data Visualization
- Business Intelligence
- Storytelling with Data

