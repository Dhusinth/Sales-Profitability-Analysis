# Sales & Profitability Analysis

## 📊 Project Overview

This project analyzes a synthetic retail sales dataset to understand sales performance, profitability, product performance, regional performance, and the impact of discounts.

**Tools used:**
- **Excel** — data analysis, PivotTables, calculations, charts, and business insights
- **Power BI** — interactive dashboard and visualization

The project is designed as an intermediate-level Data Analyst portfolio project focused on practical, interview-friendly business analysis.

---

## 🎯 Business Questions

1. What are the total sales and total profit?
2. How do sales change month by month?
3. Which product categories generate the most sales?
4. Which categories generate the most profit?
5. What are the top 10 products by sales?
6. Which regions generate the most sales?
7. What is the overall profit margin?
8. How does discount affect profitability?

---

## 🗂️ Dataset

The dataset contains **4,000 retail order-line records** across customers, products, categories, regions, and order dates.

| Column | Description |
|---|---|
| Order ID | Unique order identifier |
| Order Date | Date when the order was placed |
| Customer ID | Unique customer identifier |
| Customer Name | Customer name |
| Region | Sales region |
| State | Customer state |
| Category | Product category |
| Sub-Category | Product sub-category |
| Product | Product name |
| Quantity | Number of units sold |
| Unit Price | Price per unit |
| Discount | Discount applied |
| Sales | Revenue generated |
| Cost | Product cost |
| Profit | Profit generated |

---

## 🛠️ Tools Used

### Excel

Used for:
- Data inspection
- Excel Tables
- PivotTables
- Date grouping
- Sales and profit analysis
- Top 10 product analysis
- Regional analysis
- Profit margin calculation
- Discount analysis
- Charts

### Power BI

Used for:
- KPI cards
- Monthly sales trend
- Sales by category
- Profit by category
- Sales by region
- Category slicer
- Region slicer

---

## 📈 Excel Analysis

### 1. Overall Sales & Profit

| Metric | Result |
|---|---:|
| Total Sales | ₹3,47,53,439 |
| Total Profit | ₹80,13,309 |

### 2. Monthly Sales Trend

Sales were analyzed month by month across **2025 and 2026** using PivotTable date grouping.

### 3. Sales by Category

| Category | Sales |
|---|---:|
| Furniture | ₹1,41,01,035 |
| Electronics | ₹1,19,29,040 |
| Home Appliances | ₹73,73,445 |
| Office Supplies | ₹13,49,919 |

### 4. Profit by Category

| Category | Profit |
|---|---:|
| Furniture | ₹31,42,435 |
| Electronics | ₹26,91,280 |
| Home Appliances | ₹17,31,495 |
| Office Supplies | ₹4,48,099 |

### 5. Top 10 Products by Sales

| Rank | Product | Sales |
|---:|---|---:|
| 1 | Monitor 24-inch | ₹66,11,325 |
| 2 | Office Chair | ₹46,67,625 |
| 3 | Air Fryer | ₹36,43,780 |
| 4 | Study Table | ₹35,23,770 |
| 5 | Filing Cabinet | ₹34,65,000 |
| 6 | Bookshelf | ₹24,44,640 |
| 7 | Mixer Grinder | ₹19,00,920 |
| 8 | Headphones | ₹17,65,260 |
| 9 | Bluetooth Speaker | ₹12,88,870 |
| 10 | Table Fan | ₹9,75,360 |

### 6. Sales by Region

| Region | Sales |
|---|---:|
| South | ₹1,47,37,557 |
| West | ₹95,11,002 |
| North | ₹62,88,801 |
| East | ₹42,16,081 |

### 7. Overall Profit Margin

**Profit Margin: 23.06%**

This means the business generates approximately **₹23.06 in profit for every ₹100 of sales**.

### 8. Discount vs Profitability

| Discount | Sales | Profit |
|---:|---:|---:|
| 0% | ₹60,21,380 | ₹18,94,670 |
| 5% | ₹72,52,386 | ₹20,08,506 |
| 10% | ₹82,13,301 | ₹19,62,601 |
| 15% | ₹74,79,499 | ₹14,39,309 |
| 20% | ₹39,08,184 | ₹5,47,814 |
| 25% | ₹18,78,690 | ₹1,60,410 |

Higher discount levels are associated with lower profit margins.

---

## 📊 Power BI Dashboard

The dashboard contains:

### KPIs
- **Total Sales:** ₹34.75M
- **Total Profit:** ₹8.01M
- **Total Orders:** 4K
- **Profit Margin:** 23.06%

### Visuals
- Monthly Sales Trend
- Sales by Category
- Profit by Category
- Sales by Region
- Category slicer
- Region slicer

### Dashboard Preview

![Sales & Profitability Dashboard](powerbi/dashboard.png)

---

## 💡 Key Business Insights

1. **Furniture** is the strongest category, generating the highest sales and profit.
2. **South** is the highest-performing region, contributing approximately ₹1.47 crore in sales.
3. **Monitor 24-inch** is the top-selling product with ₹66.11 lakh in sales.
4. Overall profit margin is **23.06%**.
5. **Office Supplies** has the lowest sales and profit contribution.
6. Higher discount levels are associated with significantly lower profit margins.
7. The **25% discount level** generates only ₹1.60 lakh in profit compared with ₹18.95 lakh at 0% discount.
8. Monthly sales fluctuate considerably, making monthly trend monitoring useful for business planning.

---

## 🔄 Project Workflow

```text
Raw Sales Data
      ↓
Excel Data Analysis
      ↓
PivotTables & Business Questions
      ↓
Excel Insights
      ↓
Power BI Dashboard
      ↓
Interactive Business Reporting
```

---

## 📁 Project Structure

```text
Sales-Profitability-Analysis/
├── README.md
├── data/
│   └── sales_data.xlsx
├── excel/
│   └── Sales_Analysis.xlsx
└── powerbi/
    ├── Sales_Profitability.pbix
    └── dashboard.png
```

---

## 🚀 Skills Demonstrated

- Excel Tables
- PivotTables
- Date grouping
- Top-N analysis
- KPI calculation
- Profit margin analysis
- Data visualization
- Power BI dashboard development
- Interactive slicers
- Business insight generation
- Translating business questions into data analysis

---

## 📌 Project Scope

This project intentionally uses **only Excel and Power BI**.

No SQL, Python, or other analysis tools were used.

The goal was to build a practical, understandable, and interview-ready retail analytics project from raw data through business reporting.
