# Maven Coffee Co. Sales & Customer Analytics

## Tableau Business Intelligence Project

An interactive Tableau data analytics project analyzing **149,116 retail transactions** from Maven Coffee Co. to uncover sales trends, customer purchasing patterns, branch performance, and product performance.

The project transforms transactional sales data into interactive dashboards and actionable business insights to support decisions related to **operations, marketing, staffing, and product strategy**.

---

## Business Problem

Maven Coffee Co. operates across three store locations and offers a variety of beverage and food products.

The analysis focuses on answering:

> **How should Maven Coffee Co. allocate its product focus, branch attention, and operational strategy to improve overall sales performance?**

The project explores three main areas:

- Branch performance across store locations
- Customer purchasing patterns across dates and times
- Sales contribution by product category, type, and individual product

---

## Dataset

The dataset contains transactional sales records from Maven Coffee Co. across three New York City locations:

- Astoria
- Hell's Kitchen
- Lower Manhattan

### Dataset Overview

| Metric | Value |
|---|---:|
| Transaction Records | 149,116 |
| Period | Jan – Jun 2023 |
| Store Locations | 3 |
| Product Categories | 9 |
| Product Types | 29 |
| Product Details | 80 |
| Transaction Hours | 6:00 AM – 8:59 PM |

The dataset includes transaction date and time, quantity, store location, product information, and unit price.

---

## 🛠️ Tools & Techniques

**Tools**
- Tableau
- Tableau Calculated Fields
- Interactive Dashboard Actions
- Dashboard Filters

**Analysis**
- Data Cleaning
- KPI Analysis
- Trend Analysis
- Time-Based Analysis
- Branch Performance Analysis
- Product Segmentation
- Customer Purchasing Pattern Analysis
- Business Intelligence & Decision Support

A calculated field was created to measure sales revenue:

`Revenue = Transaction Quantity × Unit Price`

---

# Dashboard 1 — KPI Overview

The executive dashboard provides an overview of overall business performance through KPI cards, monthly revenue trends, store performance, and product-category analysis.

### Key KPIs

| KPI | Result |
|---|---:|
| Total Revenue | **$698,812** |
| Total Transactions | **149,116** |
| Average Order Value | **$4.69** |
| Top Category | **Coffee** |

### Key Finding

Monthly revenue increased from **$81,678 in January to $166,486 in June**, representing approximately **104% growth** over the six-month period.

A temporary decline occurred in February before revenue increased consistently from March through June.

---

# Dashboard 2 — Customer Buying Trends

This dashboard analyzes customer purchasing behaviour based on:

- Hour of day
- Day of week
- Month
- Revenue patterns

### Key Finding

Customer activity is heavily concentrated during the **morning period between 8:00 AM and 10:00 AM**.

Transaction volume reached its peak at approximately:

**26,713 transactions at 10:00 AM**

After 11:00 AM, transaction volume decreased by more than **50%** and remained relatively low throughout the afternoon.

Weekdays also generated stronger revenue than weekends.

### Business Implication

The pattern suggests an opportunity to:

- Allocate more staff during morning peak hours
- Prepare inventory before the morning rush
- Reduce unnecessary resources during quieter periods
- Introduce promotions to increase afternoon demand

---

# Dashboard 3 — Product & Branch Performance

The third dashboard provides interactive analysis across:

**Product Category → Product Type → Product Detail**

Users can filter the dashboard by:

- Month
- Store location
- Product category

Dashboard actions allow users to select a product category and automatically explore the corresponding product-level details.

### Branch Performance

| Store | Revenue |
|---|---:|
| Hell's Kitchen | **$236,511** |
| Astoria | **$232,244** |
| Lower Manhattan | **$230,057** |

Revenue differs by **less than 3%** between the highest- and lowest-performing locations, indicating relatively balanced performance across all three stores.

---

## Product Performance

The two largest revenue contributors were:

**Coffee — $269,952**

**Tea — $196,406**

Together, Coffee and Tea accounted for **more than 66% of total revenue**.

Among the highlighted best-selling products:

- Regular Latte — **$19,112**
- Large Cappuccino — **$17,642**

In contrast, **Packaged Chocolate generated only $4,408**, making it the lowest-performing product category in the analysis.

---

# Business Recommendations

Based on the dashboard findings, five recommendations were developed:

### 1. Optimize Morning Staffing

Increase staffing and inventory preparation during peak morning periods, particularly between **8:00 AM and 10:00 AM**.

### 2. Increase Afternoon Demand

Introduce afternoon promotions, bundled offers, or loyalty incentives during lower-traffic periods.

### 3. Use a Unified Branch Marketing Strategy

Since revenue performance differs by less than 3% across locations, broadly consistent marketing strategies can be considered across the three stores.

### 4. Prioritize High-Performing Product Lines

Continue focusing investment and promotional activity on **Coffee and Tea**, which contribute the majority of revenue.

### 5. Review Underperforming Products

Reassess the inventory strategy for **Packaged Chocolate** and consider reallocating resources toward products with stronger customer demand.

---

## Full Analysis

The complete analysis report includes:

- Business problem definition
- Dataset understanding
- Data cleaning
- Tableau dashboard development
- Calculated fields
- Interactive dashboard actions
- Trend analysis
- Product segmentation
- Business insights
- Recommendations

Download the PDF report from this repository for the complete case study.

---

## Acknowledgement

This portfolio case study was adapted from a **Business Intelligence and Analytics group academic project**. The Tableau analysis and report were developed collaboratively as part of the coursework.

---