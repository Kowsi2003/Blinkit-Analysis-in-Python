# 📊 Blinkit Sales Analysis using Python

---

## 🗂️ Dataset

* **Source**: [blinkit\_data.csv](blinkit_data.csv)
* **Features Used**:

  * Item details (`Item Type`, `Item Fat Content`, `Item Visibility`, etc.)
  * Outlet details (`Outlet Size`, `Outlet Location Type`, `Outlet Establishment Year`, etc.)
  * `Sales` column as target for analysis.

---

## ⚙️ Tools and Libraries

* Python (Jupyter Notebook / Colab)
* `pandas` for data cleaning and analysis
* `matplotlib`, `seaborn` for data visualization
* `numpy` for numerical operations

---

## 🚀 Project Objectives

✅ Perform **Exploratory Data Analysis (EDA)** on Blinkit sales data.
✅ Understand sales distribution across various categories: item type, fat content, outlet size, location type, and establishment year.
✅ Generate **business insights for sales strategy planning.**

---

## ✅ What I Did

| Step                                   | Description                                                                                      |
| -------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **1️⃣ Imported Libraries**             | Loaded pandas, numpy, matplotlib, seaborn.                                                       |
| **2️⃣ Loaded Raw Data**                | Read CSV into a pandas DataFrame.                                                                |
| **3️⃣ Initial Data Exploration**       | Used `.head()`, `.describe()`, `.info()` to view sample data, field info, and data types.        |
| **4️⃣ Data Cleaning**                  | Standardized `Item Fat Content` by replacing inconsistent labels (e.g., `LF`, `low fat`, `reg`). |
| **5️⃣ Business Requirements Analysis** | Defined KPIs to calculate **total sales and average sales**.                                     |
| **6️⃣ Visual Analysis**                | Created clear, actionable charts for each business question:                                     |

---

## 📈 Visual Analysis & Charts

✅ **Total Sales by Fat Content**

* Used a pie chart to visualize the proportion of sales between Low Fat and Regular items.

✅ **Total Sales by Item Type**

* Used a horizontal bar plot to identify which item types contribute most to sales.

✅ **Fat Content vs. Outlet Tier by Total Sales**

* Used a grouped bar chart to compare Low Fat vs. Regular sales across outlet location tiers (Tier 1, 2, 3).

✅ **Total Sales by Outlet Establishment Year**

* Used a line plot to visualize sales trends based on the year the outlet was established.

✅ **Sales by Outlet Size**

* Used a pie chart to visualize sales contribution across outlet sizes (Small, Medium, High).

✅ **Total Sales by Outlet Location Type**

* Used a horizontal bar chart to compare total sales across different outlet location types.

---

## 🪄 Key Insights

✅ Regular and Low Fat items contribute differently to total sales, indicating customer preference analysis opportunities.
✅ Certain item types contribute significantly more to sales, suggesting focus areas for inventory and marketing.
✅ Newer outlets do not always correspond to higher sales, suggesting the need for location-specific analysis.
✅ Medium-sized outlets and Tier 3 locations show substantial sales contribution.

---

## ✅ Summary

This project demonstrates:

* Data cleaning and preprocessing
* Grouping, aggregation, and KPI extraction
* Visual data storytelling
* Drawing actionable business insights from sales data using Python.
