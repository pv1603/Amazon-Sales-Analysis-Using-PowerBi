# 📊 Amazon Sales Analysis Using Power BI

This project showcases a beginner-friendly yet insightful **Amazon Sales Analysis Dashboard** built using **Power BI**. The goal is to visualize and analyze sales trends, product performance, and customer reviews over time using interactive visuals and KPIs.

---

## 🛠️ Project Setup

1. **Data Source:** Loaded an Excel file containing Amazon sales data into Power BI.
2. **Created a custom `Date Table`** for analysis:
   - `Date` = `CALENDAR(MIN(Amazon_Data[Order Date]), MAX(Amazon_Data[Order Date]))`
   - `Month Name` = `FORMAT('Date table'[Date], "mmm")`
   - `Month Number` = `MONTH('Date table'[Date])`
   - `Week` = `WEEKNUM('Date table'[Date], 1)`
   - `Quarter` = `QUARTER('Date table'[Date])`
   - `Qtr` = `CONCATENATE("Qtr ", 'Date table'[Quarter])`

---

## 📊 Key Visuals & Insights

### 🎚️ Slicers
- Product Category
- Quarter-based Sales Filter

### 🧾 Cards
- **YTD Sales**
- **QTD Sales**
- **YTD Products Sold**
- **YTD Reviews**

### 📈 Charts & Visuals
- **Pie Chart:** Sales by Product Category
- **Matrix Table:** Sales categorized by product
- **Area Chart:** Monthly Sales Trends
- **Stacked Column Chart:** Weekly Sales Distribution
- **KPI Tiles:** Sales and Review Metrics per Product Category

---

## 💡 Summary

This Power BI dashboard allows users to filter and explore Amazon sales data from multiple perspectives—by time, product category, and performance metrics. It gives a clear snapshot of how products perform over time and which areas drive the most value.

---

## 📌 Conclusion

> This is a **simple and foundational project** that demonstrates basic Power BI capabilities like creating a date table, using slicers, cards, KPIs, and various charts. While it can certainly be improved with more refined visuals and advanced modeling techniques, this version represents my initial take on sales data analysis using Power BI.

---

## 🧠 Tools Used

- **Power BI Desktop**
- **DAX**
- **Data Modeling**
- **Excel (as data source)**

---

