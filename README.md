# Profitability and Marketing Performance Analysis for an E-Commerce Startup

Business analytics project analyzing profitability, customer conversion, and marketing performance using three months of real Naver Smart Store data.

## Project Overview

This project analyzes **three months of real e-commerce operational data** from a Naver Smart Store.

The analysis integrated **18 data sources** covering sales, customers, products, marketing channels, orders, and settlement records. The objective was to identify profitability and conversion bottlenecks and translate the findings into actionable business recommendations.

Three interactive Tableau dashboards were developed to examine:

- Product- and option-level profitability
- Sales and customer conversion patterns
- Marketing-channel and product performance

## Key Findings

- Identified a **margin-revenue mismatch**, where several high-revenue products and options did not necessarily generate the highest profit margins.
- Found a substantial decline in first-purchase conversion, from **10.6% to 4.9%**, indicating a key conversion-funnel bottleneck.
- Identified **Naver Search** as a high-value acquisition channel, with **Revenue per Visitor (RPV) approximately 6× the channel median**.
- Found that coupon allocation could be improved by prioritizing **higher-margin, lower-volume products** rather than already high-volume options.
- Identified opportunities to restructure bundle promotions to improve **packaging efficiency and profitability**.

## Methodology

The analysis combined:

- Profit margin and cost-structure analysis
- Revenue per Visitor (RPV)
- Conversion Rate (CVR)
- Customer conversion-funnel analysis
- Product- and option-level performance analysis
- Marketing-channel performance analysis
- Time-based sales and purchasing-pattern analysis

Product- and option-level margins were calculated in Tableau using **LOD expressions**, incorporating product costs, packaging, shipping, commissions, and settlement costs.

## Tools

- **Tableau** — Dashboard development, LOD expressions, KPI analysis, and visualization
- **Excel** — Source-data preparation and validation
- **Naver Smart Store** — Transactional, customer, marketing, and settlement data

## Repository Contents

- `index.html` — Full project report and dashboard analysis
- `ecommerce_profitability_marketing_analysis.qmd` — Quarto source document

## Full Project

The complete analysis, including dashboard outputs, methodology, and detailed business insights, is available through the GitHub Pages version of this repository.

> **Live Portfolio:** Link will be added after GitHub Pages deployment.

## Data Confidentiality

This project was conducted using **real transactional and operational data from an e-commerce startup**.

To protect **business confidentiality and customer privacy**, the raw datasets and Tableau packaged workbook (`.twbx`) are not publicly available. This repository provides the project methodology, aggregated dashboard outputs, analytical findings, and business recommendations without exposing the underlying confidential data.
