# 🛍️ E-Commerce Sales & Returns Dashboard – Category Performance & Monthly Trends

[![Excel](https://img.shields.io/badge/Excel-Dashboard-green?logo=microsoft-excel)](https://www.microsoft.com/excel)
[![E-Commerce Analytics](https://img.shields.io/badge/Type-Sales_Analytics-blue)](https://github.com)
[![Performance Tracking](https://img.shields.io/badge/Analysis-Returns_Trends-orange)](https://github.com)

A comprehensive Excel solution built to analyze one year of e-commerce performance across sales, orders, and returns using pivot tables and interactive charts. It transforms raw transactional data into actionable insights — enabling teams to understand category-wise performance, product trends, monthly fluctuations, and return patterns for data-driven business optimization.

---

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Project Objective](#project-objective)
- [Dataset Description](#dataset-description)
- [Pivot Tables Used](#pivot-tables-used)
- [Dashboard Components](#dashboard-components)
- [Installation & Prerequisites](#installation--prerequisites)
- [How to Use](#how-to-use)
- [Key Insights](#key-insights)
- [Tech Stack](#tech-stack)
- [Skills Demonstrated](#skills-demonstrated)

---

## 📊 Project Overview

This Excel project provides an **interactive analysis of one year of e-commerce performance** using pivot tables, pivot charts, and dynamic filtering. It enables monitoring of:

- 💰 **Revenue by product category** (Category-wise revenue distribution)
- 📦 **Units sold by product category** (Volume analysis by category)
- 📅 **Monthly orders trend** (Seasonal patterns and order fluctuations)
- 🏆 **Units sold per product** (Top-performing and low-performing products)
- 🔄 **Monthly returns trend** (Return patterns and quality indicators)
- 🔍 **Dynamic category filtering** (Category-wise performance drill-down)

---

## 🎯 Project Objective

To analyze one year of e-commerce performance and provide insights for strategic optimization:

✅ **Identify top-performing product categories** by revenue and volume  
✅ **Track monthly order trends** and seasonal patterns  
✅ **Analyze monthly returns** and quality indicators  
✅ **Discover best and worst-performing products** within categories  
✅ **Enable dynamic filtering** by product category for detailed analysis  
✅ **Support data-driven decisions** on inventory and marketing strategy  

---

## ⚙️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Microsoft Excel** | Data aggregation, pivot tables, dashboard creation |
| **Pivot Tables** | Revenue, units, and returns aggregation by category |
| **Pivot Charts** | Visual trends (Bar, Line, Column charts) |
| **Slicers** | Dynamic filtering by product category |
| **Data Labels & Conditional Formatting** | Clarity and visual highlighting |

---

## 📁 Dataset Description

### File Details

**File Name:** Ecommerce-Sales-Revenue-Dashboard-[Excel].xlsx

**Data Range:** September 2024 – September 2025

**Total Records:** ~1,000 rows (simulated transactional data)

### Columns

| Column | Description |
|--------|-------------|
| **Order_ID** | Unique order identifier |
| **Product_Category** | Category classification (Books, Electronics, Sports, Clothing, Home & Kitchen, Toys) |
| **Product_Name** | Specific product name within category |
| **Revenue** | Sales revenue per order |
| **Units_Sold** | Number of units sold |
| **Returned_Products** | Number of products returned |
| **Month-Year** | Transaction date in Month-Year format |

---

## 🧮 Pivot Tables Used

### Pivot Table 1 – Revenue by Product Category

| Product Category | Sum of Revenue |
|-----------------|----------------|
| **Books** | 227,869 |
| **Electronics** | 214,541 |
| **Sports** | 208,453 |
| **Clothing** | 207,984 |
| **Home & Kitchen** | 206,132 |
| **Grand Total** | 1,064,979 |

**Chart Used:** Bar Chart – Revenue by Product Category

**Insight:** Books generate the highest total revenue (₹227,869). Overall revenue difference among categories is narrow, showing balanced category performance.

---

### Pivot Table 2 – Units Sold by Product Category

| Product Category | Sum of Units Sold |
|-----------------|------------------|
| **Books** | 892 |
| **Electronics** | 815 |
| **Sports** | 782 |
| **Clothing** | 777 |
| **Toys** | 768 |
| **Grand Total** | 4,034 |

**Chart Used:** Bar Chart – Units Sold by Product Category

**Insight:** Units sold trend mirrors revenue—Books lead with highest units (892), confirming strong demand and profitability.

---

### Pivot Table 3 – Monthly Orders Trend

| Month-Year | Count of Orders |
|-----------|-----------------|
| **Sep-24** | 36 |
| **Oct-24** | 68 |
| **Nov-24** | 82 |
| **Dec-24** | 103 |
| **Jan-25** | 85 |
| **Feb-25** | 72 |
| **Mar-25** | 77 |
| **Apr-25** | 86 |
| **May-25** | 71 |
| **Jun-25** | 73 |
| **Jul-25** | 81 |
| **Aug-25** | 76 |
| **Sep-25** | 70 |

**Chart Used:** Line Chart – Orders Trend by Month

**Insights:**
- Peak demand in Dec 2024 (103 orders) — holiday season
- Lowest activity in Sep 2024 (36 orders)
- Stable order volumes post-Jan 2025 indicate steady growth (70–90 orders per month)

---

### Pivot Table 4 – Units Sold per Product (Category + Product)

| Product Category | Product Name | Sum of Units Sold |
|-----------------|--------------|------------------|
| **Books** | Self-Help Book | 230 |
| **Books** | Novel | 220 |
| **Sports** | Basketball | 212 |
| **Sports** | Football | 190 |
| **Clothing** | T-Shirt | 180 |
| **Toys** | Board Games | 119 |

**Chart Used:** Bar Chart – Units Sold per Product

**Insight:** Self-Help Books and Basketballs are top sellers. Board Games have relatively lower performance. Each category has clear internal leaders highlighting customer preferences.

---

### Pivot Table 5 – Monthly Returns

| Month-Year | Sum of Returned Products |
|-----------|------------------------|
| **Sep-24** | 3 |
| **Oct-24** | 15 |
| **Nov-24** | 7 |
| **Dec-24** | 13 |
| **Jan-25** | 8 |
| **Feb-25** | 10 |
| **Mar-25** | 9 |
| **Apr-25** | 6 |
| **May-25** | 8 |
| **Jun-25** | 9 |
| **Jul-25** | 7 |
| **Aug-25** | 5 |
| **Sep-25** | 1 |

**Chart Used:** Column Chart – Monthly Returns Trend

**Insights:**
- Highest returns in Oct 2024 (15) and Dec 2024 (13)
- Minimal returns afterward — possibly better quality control or accurate product listings
- Overall returns remain moderate throughout the year

---

### Pivot Table 6 – Product Category Slicer

**Slicer Field:** Product_Category

**Connected to:** All five pivot tables

**Functionality:** Enables instant filtering across all charts to analyze a single category's metrics (revenue, units, returns, etc.)

---

## 📈 Dashboard Components

### 1️⃣ Revenue by Product Category

**Chart Type:** Horizontal Bar Chart

**Purpose:** Visualizes which categories drive the most revenue

**Key Finding:** Books generated the highest revenue (~₹227,869), Home & Kitchen lowest (~₹206,132)

---

### 2️⃣ Units Sold by Product Category

**Chart Type:** Horizontal Bar Chart

**Purpose:** Compares category-wise volume

**Key Finding:** Books lead with highest number of units sold (892 units), Toys lowest (768 units)

---

### 3️⃣ Orders Trend by Month

**Chart Type:** Line Chart with Data Points

**Purpose:** Tracks monthly trends and seasonality

**Key Findings:**
- Peak: December 2024 – 103 orders (holiday season)
- Low: September 2024 – 36 orders (off-season)
- Stable: January to August 2025 (70–90 orders per month)

---

### 4️⃣ Units Sold per Product (by Subcategory)

**Chart Type:** Horizontal Bar Chart

**Purpose:** Identifies top-performing and low-performing individual products

**Top Performers:**
- Self-Help Books – 230 units sold
- Basketball – 212 units sold

**Lowest Performer:**
- Board Games – 119 units sold

---

### 5️⃣ Monthly Returns Trend

**Chart Type:** Column Chart

**Purpose:** Highlights months with high returns and potential quality issues

**Key Findings:**
- Peak: October 2024 – 15 returns
- Lowest: September 2024 (3 returns) and September 2025 (1 return)
- Overall returns remain moderate (6–10 per month)

---

### 6️⃣ Product Category Slicer (Filter)

**Purpose:** Adds interactivity and ease of exploration

**Functionality:** Allows viewers to filter the entire dashboard to view performance metrics for a specific category only (e.g., just "Books" or "Electronics"). All charts update instantly to reflect the selected filter.

---

## ⚙️ Installation & Prerequisites

### System Requirements

- **Microsoft Excel** (2016 or later recommended)
- **Windows 10** or later / **macOS** with Excel installed
- **2GB RAM** minimum (4GB+ recommended)
- **100MB** free disk space

### Installation Steps

```
1. Download the Excel File
   → Ecommerce-Sales-Revenue-Dashboard-[Excel].xlsx

2. Open Microsoft Excel

3. File → Open → Select Ecommerce-Sales-Revenue-Dashboard-[Excel].xlsx

4. Wait for file to load completely

5. Navigate to Dashboard sheet to view visuals
```

---

## 📊 How to Use

### Accessing the Dashboard

**Step 1: Open the File**
```
Microsoft Excel → File → Open → Ecommerce-Sales-Revenue-Dashboard-[Excel].xlsx
```

**Step 2: Navigate to Dashboard Sheet**
- Select the Dashboard tab/sheet from the sheet tabs at the bottom
- All visualizations and metrics are displayed on this sheet

**Step 3: Use Interactive Elements**

| Feature | Action |
|---------|--------|
| **Revenue Chart** | View total revenue contribution by category |
| **Units Sold Chart** | Compare volume across product categories |
| **Orders Trend Chart** | Track monthly order patterns and seasonality |
| **Products Chart** | Identify top and bottom-performing products |
| **Returns Chart** | Monitor monthly return trends and patterns |
| **Category Slicer** | Click category names to filter all charts instantly |

### Interpreting the Data

- **Revenue Chart** → Which categories generate the most income
- **Units Sold Chart** → Volume distribution across categories
- **Orders Trend Line Chart** → Seasonal patterns and peak demand periods
- **Products Bar Chart** → Individual product performance within categories
- **Returns Column Chart** → Return volume by month and quality indicators
- **Category Slicer** → Drill down into specific category metrics

---

## 💡 Key Insights

### Category Performance

✅ **Books lead in revenue** (₹227,869) and units (892), indicating strong demand and profitability

✅ **Balanced portfolio** across categories — only ₹36K difference between highest and lowest revenue categories

✅ **Home & Kitchen lowest** in revenue (₹206,132) but still contributes meaningfully to portfolio

### Product Level Insights

✅ **Self-Help Books and Basketball** are top performers (230 and 212 units respectively)

✅ **Board Games underperforming** (119 units) — lowest within tracked products

✅ **Each category has clear leaders** — highlighting customer preference patterns

### Monthly Trends

✅ **December peak** with 103 orders — strong holiday season demand

✅ **Stable post-holiday** with 70–90 orders per month (Jan–Aug 2025) showing sustainable growth

✅ **September low** with only 36 orders in 2024, improving to 70 in Sept 2025

### Return Patterns

✅ **October 2024 spike** with 15 returns — possible post-holiday or product quality issues

✅ **Minimal recent returns** (1 in Sept 2025) — indicates improved quality control or accurate listings

✅ **Overall returns moderate** — 6–10 per month on average across the year

### Overall Trend

✅ **Sales peaked during holidays** and stabilized through 2025 at consistent levels

✅ **Consistent product mix** with balanced category contributions

---

## 🧰 Tech Stack

| Component | Technology |
|-----------|------------|
| **Platform** | Microsoft Excel |
| **Analysis Tool** | Pivot Tables & Pivot Charts |
| **Data Visualization** | Excel Charts (Bar, Line, Column) |
| **Interactivity** | Slicers & Dynamic Filtering |
| **Data Source** | Simulated e-commerce transaction dataset |

---

## 📁 Project Files

**File:** `Ecommerce-Sales-Revenue-Dashboard-[Excel].xlsx`
- Excel workbook with transactional data and interactive dashboard
- Contains pivot tables, pivot charts, slicers, and complete sales analysis
- Ready for immediate use and business analysis

---

## 💼 Skills Demonstrated

✅ **Data Summarization** through pivot tables  
✅ **Trend Analysis** across monthly and categorical dimensions  
✅ **Pivot Table Creation** for multi-level aggregation  
✅ **Pivot Chart Design** for effective visualization  
✅ **Slicer Implementation** for interactive filtering  
✅ **Data Labeling & Conditional Formatting** for clarity  
✅ **Dashboard Creation** with multiple coordinated visuals  
✅ **E-Commerce Analytics** and performance interpretation  
✅ **Seasonal Pattern Recognition** from monthly trends  
✅ **Business Reporting** for stakeholder communication  

---

## 📝 Notes

- Dataset contains approximately 1,000 simulated e-commerce transaction records
- Data spans one full year from September 2024 to September 2025
- All pivot tables and charts are production-ready and optimized
- Slicer enables flexible filtering across all dashboard elements simultaneously
- Revenue and units sold trends are consistent, indicating reliable performance data
- Return analysis highlights quality and operational efficiency
- Dashboard supports inventory planning, marketing strategy, and performance review

---

*This Excel-based E-Commerce Sales & Returns Dashboard demonstrates practical e-commerce analytics expertise, combining transactional data aggregation through pivot tables, multi-dimensional trend analysis, and interactive visualization to enable data-driven decision-making through comprehensive monitoring of category performance, product-level insights, monthly seasonality patterns, and return trends across one year of operational data.*
