# 📊 Sales MIS Dashboard & Performance Analysis

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)
![Dataset](https://img.shields.io/badge/Dataset-Kaggle%20Retail%20Sales-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

---

## 📌 Project Objective

To build a complete **MIS (Management Information System) Report** using Microsoft Excel that analyzes retail sales data across regions, product categories, and time periods — simulating real-world reporting done by Data Analyst and MIS Executive teams in companies.

---

## 🛠️ Tools Used

- **Microsoft Excel** — PivotTables, Slicers, Dynamic Charts, Macros, Power Query
- **Dataset** — [Superstore Sales Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) (Kaggle) — ~10,000 rows

---

## 📂 Project Structure

```
Sales-MIS-Dashboard/
│
├── SALES_MIS_PROJECT_MADHAV.xlsx   # Main Excel file with all reports
├── screenshots/
│   ├── monthly_sales_trend.png     # Monthly Sales Line Chart
│   ├── top_products.png            # Top 10 Products Bar Chart
│   ├── regional_sales.png          # Regional Sales Clustered Bar Chart
│   └── category_sales.png          # Category Sales Pie Chart
└── README.md
```

---

## 🧹 Data Cleaning Steps

Before building the reports, the raw dataset was cleaned:

- Checked for and removed **duplicate Order IDs**
- Verified no **blank cells** in key columns (Sales, Region, Category)
- Reformatted **Order Date** column to `DD-MM-YYYY`
- Added **Month** column using `=TEXT(OrderDate,"MMM-YYYY")` for time-series analysis
- Added **Year** column using `=YEAR(OrderDate)` for year-on-year comparisons
- Ensured **Sales column** was formatted as numeric (not text)

---

## 📊 Reports Built

### 1. 📈 Monthly Sales Trend (2015–2018)
- PivotTable with Month in Rows and Year in Columns
- Line chart showing sales trend across all 4 years
- **Key Finding:** November and December are peak sales months every year

### 2. 🏆 Top 10 Products by Revenue
- PivotTable sorted by Sales (Largest to Smallest)
- Top 10 filter applied
- Horizontal bar chart for easy comparison
- **Key Finding:** Hewlett Packard LaserJet 3310 Copier is the top-selling product

### 3. 🌍 Regional Sales Performance
- PivotTable with Region in Rows and Year in Columns
- Clustered bar chart with interactive Region slicer
- **Key Finding:** West region is the top performer with $325,811 in total revenue

### 4. 🥧 Sales by Category
- Drill-down PivotTable with Category and Sub-Category
- Pie chart showing percentage split with data labels
- Interactive Category and Sub-Category slicers
- **Key Finding:** Technology leads at 35%, followed by Furniture (33%) and Office Supplies (32%)

---

## 🔍 Key Insights

| Metric | Value |
|--------|-------|
| 📦 Total Revenue (2015–2018) | **$1,076,111** |
| 🌍 Top Region | **West — $325,811 (30% of total)** |
| 🛍️ Top Category | **Technology — 35% revenue share** |
| 📅 Peak Sales Months | **November & December (every year)** |
| 📈 Revenue Growth | **70% growth from 2015 to 2018** |
| 🏆 Best Year | **2018 — $350,901** |

---

## 💡 Business Recommendations

Based on the analysis:

1. **Stock up on Technology products** before Q4 (Oct–Dec) to capitalize on seasonal demand peaks
2. **Invest more in West and East regions** as they consistently outperform Central and South
3. **Review South region strategy** — it lags behind other regions across all years and needs targeted attention
4. **Focus promotions in November–December** when sales naturally spike — maximize revenue during peak season

---


---

## 👤 Author

**Madhav Ranga**
- 📧 madhavranga08@gmail.com
- 🔗 [LinkedIn](https://linkedin.com/in/madhav-ranga)
- 📍 Delhi, India

---

## 📚 Learnings from this Project

- How to structure and clean raw data before analysis
- Building multi-sheet MIS reports using PivotTables
- Creating interactive dashboards using Slicers
- Deriving business insights from data and presenting them clearly
- Understanding seasonal trends and regional performance patterns

---

*This project was built as part of my Data Analyst learning journey to demonstrate practical Excel and MIS reporting skills.*
