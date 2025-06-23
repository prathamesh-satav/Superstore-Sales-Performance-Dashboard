# 📊 Superstore Sales Performance Dashboard | Power BI Project

## 📌 Overview

This Power BI dashboard analyzes retail sales data from the popular **Sample Superstore** dataset to extract meaningful business insights around sales, profit, product performance, customer segments, and regional trends. This beginner-friendly project is ideal for showcasing data visualization, dashboard design, and business intelligence skills as an aspiring data analyst.

---

## 🎯 Project Goals

- Create a visually engaging and interactive executive dashboard
- Summarize key performance indicators (KPIs) for quick insight
- Identify high-performing product categories and customer segments
- Track sales performance over time and across regions
- Demonstrate core Power BI skills for a data analyst portfolio

---

## 📊 Dashboard Features

| Feature | Description |
|--------|-------------|
| **KPI Cards** | Track Total Sales, Total Profit, Total Quantity, and Average Discount |
| **Line Chart** | Visualize Sales trends by month over time |
| **Bar Chart** | Compare Sales across Product Sub-Categories grouped by Category |
| **Map** | Analyze Sales performance across U.S. States (or Bar chart as fallback) |
| **Pie Chart** | Show Profit contribution by Customer Segment |
| **Slicers** | Enable filtering by Region, Category, and Year (Order Date) |

---

## 🛠 Tools & Technologies

- **Power BI Desktop**
- **DAX (Data Analysis Expressions)** for KPI measures
- **Power Query** (minimal – data already clean)
- **Sample - Superstore.csv** as dataset

---

## 📂 Dataset Information

- **Source**: [Kaggle – Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Format**: CSV
- **Size**: ~10,000 rows
- **Fields Include**:
  - `Order Date`, `Sales`, `Profit`, `Discount`, `Quantity`
  - `Category`, `Sub-Category`, `Segment`, `Region`, `State`, `Ship Mode`

---

## 📈 Key Insights Uncovered

- 📦 **Office Supplies and Technology** are the highest grossing categories
- 💰 The **Corporate Segment** contributes the most to profit
- 🌍 **California, New York, and Texas** drive the largest portion of sales
- 📉 Certain sub-categories (e.g. Tables) show negative profit despite high sales
- 🕒 Sales show consistent growth with seasonality during Q4

---

## 🧮 DAX Measures Used

```DAX
Total Sales = SUM('Superstore'[Sales])
Total Profit = SUM('Superstore'[Profit])
Total Quantity = SUM('Superstore'[Quantity])
Average Discount = AVERAGE('Superstore'[Discount])
MonthYear = FORMAT('Superstore'[Order Date], "MMM YYYY")
