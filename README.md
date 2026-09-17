# Management Consulting Analytics in ESG & Financial Performance

> A consulting-style analytics project that quantifies the relationship between ESG performance and financial outcomes using regression modelling, engineered ESG metrics, Excel, and Tableau.

<p align="left">
  <img src="https://img.shields.io/badge/Excel-Regression%20Analysis-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white">
  <img src="https://img.shields.io/badge/Tableau-Interactive%20Dashboard-E97627?style=for-the-badge&logo=tableau&logoColor=white">
  <img src="https://img.shields.io/badge/Domain-ESG%20Analytics-0F766E?style=for-the-badge">
  <img src="https://img.shields.io/badge/Framework-Management%20Consulting-111827?style=for-the-badge">
</p>

---

## Executive Summary

Environmental, Social & Governance (ESG) reporting has evolved from a compliance exercise into a strategic driver of firm value. This project develops a **diagnostic consulting framework** to evaluate whether stronger ESG performance is associated with higher profitability, market valuation, and sustainable growth among Indonesian publicly listed companies.

The analysis combines statistical modelling with executive dashboards to deliver decision-ready insights for consultants, investors, CFOs, and ESG strategy teams.

---

## Business Problem

Mid-sized companies increasingly disclose ESG information, yet many lack evidence of **which sustainability initiatives actually create financial value**.

This project addresses that challenge by answering:

- Does higher ESG performance improve ROA and Tobin's Q?
- Which sectors generate the highest return per unit of ESG investment?
- How can executives benchmark ESG maturity using financial diagnostics rather than descriptive reporting?

---

## Project Highlights

| Metric | Value |
|---------|------:|
| Public Companies | **14+** |
| ESG & Financial Observations | **90+** |
| Financial KPIs | **ROA · Tobin's Q · SGR** |
| Engineered ESG Metrics | **3** |
| Interactive Tableau Dashboards | **4** |
| Statistical Models | **Correlation + Simple & Multiple Regression** |

---

# Dashboard Preview

> Replace these placeholders with exported Tableau screenshots.

## Dashboard 1 — ESG Distribution

![ESG Distribution](images/dashboard_1.png)

Visualizes ESG score distribution, quartile segmentation, and sector-wise ESG maturity through histograms and boxplots.

---

## Dashboard 2 — ESG vs Financial Performance

![ESG Financial](images/dashboard_2.png)

Compares ESG Score against:

- Return on Assets (ROA)
- Tobin's Q
- Profitability Gap

using interactive scatter plots and quadrant analysis.

---

## Dashboard 3 — Sector Benchmarking

![Sector Benchmark](images/dashboard_3.png)

Benchmarks ESG maturity and profitability across:

- Financials
- Consumer Discretionary
- Basic Materials

with heatmaps, growth comparisons, and ESG quartiles.

---

## Dashboard 4 — ESG Impact Index

![Impact Index](images/dashboard_4.png)

Signature consulting dashboard combining:

- Growth-Adjusted ESG
- Profitability Gap
- Leverage-to-ESG Ratio
- ESG Impact Index

to identify high-value ESG performers.

---

# Consulting Methodology

```text
Secondary ESG & Financial Data
                │
                ▼
Data Cleaning & Standardization
                │
                ▼
Feature Engineering
(ESG Normalization + Diagnostic Metrics)
                │
                ▼
Correlation Analysis
                │
                ▼
Regression Modelling
                │
                ▼
Tableau Executive Dashboards
                │
                ▼
Strategic ESG Recommendations
```

---

# Feature Engineering

Unlike conventional ESG studies, this project creates three firm-level diagnostic indicators:

| Engineered Metric | Formula | Business Purpose |
|------------------|---------|------------------|
| **Profitability Gap** | Firm ROA − Sector Average ROA | Measures relative operational performance |
| **Growth-Adjusted ESG** | ESG Score × Sustainable Growth Rate | Identifies financially efficient ESG leaders |
| **Leverage-to-ESG Ratio** | Leverage ÷ ESG Score | Evaluates financial risk against ESG maturity |

These metrics improve firm-level benchmarking beyond raw ESG scores.

---

# Statistical Analysis

### Correlation Analysis

Evaluated relationships between:

- ESG Score
- ROA
- Tobin's Q
- Sustainable Growth Rate
- Leverage Ratio

to identify preliminary financial associations.

### Simple Regression

ROA = β₀ + β₁(ESG Performance)

Tests whether ESG independently predicts profitability.

### Multiple Regression

ROA = β₀ + β₁(ESG) + β₂(Leverage) + β₃(SGR)

Controls for financial structure and sustainable growth to isolate ESG influence.

---

# Business Questions Solved

- Does ESG positively influence profitability?
- Do Top ESG quartile firms outperform lower quartiles?
- Which sectors demonstrate stronger ESG-financial alignment?
- Can engineered ESG metrics improve investment prioritization?
- How should firms benchmark ESG maturity against competitors?

---

# Repository Structure

```text
management-consulting-esg-financial-analytics
│
├── README.md
├── LICENSE
├── .gitignore
│
├── data
│   ├── esg_financial_dataset.xlsx
│   └── data_dictionary.md
│
├── dashboard
│   └── ESG_Executive_Dashboard.twbx
│
├── reports
│   ├── Final_Consulting_Report.pdf
│   └── Research_Design.pdf
│
└── images
    ├── dashboard_1.png
    ├── dashboard_2.png
    ├── dashboard_3.png
    └── dashboard_4.png
```

---

# Tech Stack

| Category | Tools |
|----------|-------|
| Data Cleaning | Microsoft Excel |
| Statistical Analysis | Correlation & Regression |
| Financial Analytics | ROA, Tobin's Q, SGR |
| Visualization | Tableau |
| Consulting | Benchmarking, ESG Impact Index |

---

# Key Deliverables

- ESG-normalized financial dataset
- Correlation matrix
- Simple & Multiple Regression models
- ESG Quartile benchmarking
- Sector comparison dashboards
- ESG Impact Index framework
- Executive consulting report

---

# Business Value

This project demonstrates how ESG data can be transformed into **decision-support analytics** rather than sustainability reporting alone. The framework enables organizations to benchmark ESG maturity, identify profitability gaps, and prioritize sustainability investments with measurable financial impact.

---

## Author

**Ishika Pawar**

Data Analytics • ESG Analytics • Financial Analytics • Management Consulting
