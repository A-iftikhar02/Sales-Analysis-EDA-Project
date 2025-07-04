# 🛒  Sales Analysis – EDA Project

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a **Superstore retail dataset** to uncover insights about sales performance, product demand, and regional profitability. The goal is to simulate a real-world data analyst's role — cleaning data, analyzing trends, and presenting insights clearly.

This is the second project in my journey toward becoming a professional **Data Analyst**.

---

## 📊 Key Insights

- The **Technology** category contributes the most to overall sales.
- The **West and East** regions generate the highest revenue.
- **November and December** show higher sales volumes — indicating peak shopping seasons.
- Most orders are placed during **weekdays**, especially on **Tuesdays and Wednesdays**.
- The **Standard Class** shipping mode is most frequently used.
- California and New York are the top-performing states in terms of sales.

---

## 🧠 What I Did – Project Phases

### ✅ Phase 1: Data Exploration
- Viewed structure and shape of the dataset
- Identified key columns: `Product Name`, `Sales`, `Category`, `Order Date`, `Region`, etc.
- Found missing values in `Postal Code` (only 11 rows) and skipped imputation

### ✅ Phase 2: Data Cleaning & Feature Engineering
- Extracted `Order Year`, `Order Month`, and `Weekday` from `Order Date`
- Grouped data to analyze sales by:
  - Category
  - Region
  - Time (Monthly trends)

### ✅ Phase 3: Insights & Visualizations
- Used `matplotlib` and `seaborn` for:
  - Line plots of monthly sales trends
  - Bar plots for sales by category and region
  - Heatmaps for category-region performance
- Answered analytical questions using `groupby()` and `.sum()`

### ✅ Phase 4: Documentation
- Polished the notebook
- Prepared a professional GitHub `README.md`
- Added challenges faced and key learnings

---

## ⚠️ Challenges I Faced

- ❌ Initially forgot to sort the multi-indexed grouped sales data by month
- ❌ Confused why `pivot_table` was better than regular `groupby` in heatmaps
- ❌ Forgot to rotate x-axis ticks in visualizations causing clutter

✅ Fixed them all by:
- Using `.sort_values()` for better trend clarity
- Learning to use `pivot_table()` for heatmap formatting
- Using `plt.xticks(rotation=45)` and `plt.tight_layout()`

---

## 🛠 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn

---

## 📂 Folder Structure

Retail_Sales_EDA_Project/
├── Superstore_EDA.py # Python file with data cleaning and EDA
├── superstore.csv # Dataset
└── README.md # Project summary and reflection



---

## ⚙️ How to Run the Project

1. Open the project folder in VS Code.
2. Open `Sales_EDA.ipynb`.
3. Run it step-by-step using the terminal or Python interactive window.

---

## 📥 Dataset

The dataset is a public retail dataset known as **Superstore** and widely used in EDA practice. It contains fictional sales transactions including order details, customer info, and shipping modes.

---

## 📝 Conclusion

This project helped me:
- Apply real-world **EDA skills**
- Learn effective use of `groupby()` and `pivot_table()`
- Visualize complex sales data in clear formats
- Prepare for **Data Analyst job roles**

> 💼 This is part of my portfolio-building journey. More projects coming soon!