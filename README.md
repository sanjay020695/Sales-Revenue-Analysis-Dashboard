# Sales-Revenue-Analysis-Dashboard
Interactive Power BI dashboard analyzing $217K sales revenue &amp; 2K units sold with dynamic DAX metrics and a custom high-contrast dark theme.
# 📊 Sales & Revenue Analysis Dashboard

An executive-ready, high-interactive Power BI dashboard designed to analyze 6 months of sales performance, monthly revenue trends, and product-specific profitability. This project demonstrates advanced data modeling, DAX measures, and modern visual UI/UX design.

---

## 🚀 Live Dashboard Preview
![Sales & Revenue Dashboard](Screenshot_2026-06-20_172555.jpg)
*(Note: Upload your dashboard screenshot with the exact file name 'Screenshot_2026-06-20_172555.jpg' in the root directory of this repository so it displays here).*

---

## 🧠 Business Performance & Insights (Based on Data)

* **Financial Health:** The business generated a **Total Revenue of $217K** with **2K Units Sold** over the 6-month period.
* **Top Revenue Driver:** **Electronics** is the leading product category, contributing over **$100K+** to the total revenue, followed by **Software** (~$68K). 
* **Monthly Growth Trend:** Sales showed strong upward momentum starting from **January ($29K)**, peaking significantly in **June at $49K** (representing an **~69% increase** in monthly revenue).
* **Low Margin/Volume Categories:** **Accessories** and **Apparel** represent the lowest revenue share, indicating potential areas for marketing optimization or pricing strategy shifts.

---

## 🛠️ Tech Stack & Tools Used
* **Platform:** Microsoft Power BI Desktop
* **Data Source:** CSV (Mock Sales & Revenue Dataset)
* **Calculations:** DAX (Data Analysis Expressions)

---

## 📐 Data Model & Custom DAX Measures

To keep the visuals and cards highly responsive to slicer actions (Region and Product Category), the following measures were configured:

1. **Total Revenue:**
   ```dax
   Total Revenue = SUM(sales_data[Revenue_USD])


Total Units Sold:

Total Units Sold = SUM(sales_data[Units_Sold])


Average Order Value (AOV):

Average Order Value = DIVIDE([Total Revenue], [Total Units Sold])


⚙️ Interactive Dashboard Features Shown in Screenshot

Interactive KPI Cards: Instantly displays $217K Revenue and 2K Units Sold with distinct drop-shadow container styling.

Top-Performing Products Bar Chart: A clean, horizontal bar chart highlighting category contribution with custom lime-green visual fills.

Monthly Revenue Trends Area Chart: Highlighting cyclical sales patterns with a soft violet area overlay and clear data labels for each month.

Slicers (Filters): * Region Filter: Slice by East, North, South, West.

Product Category Filter: Slice by Accessories, Apparel, Electronics, Software.
