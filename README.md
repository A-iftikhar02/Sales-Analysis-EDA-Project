# Retail Sales Data Analysis – EDA with Python

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on the *Superstore retail dataset* to uncover business insights related to product categories, regional performance, and time-based trends.

The goal is to demonstrate practical EDA skills using **Python**, **Pandas**, and **Matplotlib**, building a strong portfolio project suitable for **data analyst roles**.

---

## 🧠 Key Insights

* **Technology** category generated the highest total sales.
* The **West** and **East** regions contributed the most to overall revenue.
* The **Office Supplies** category had lower sales but high transaction volume.
* **December** and **November** saw significant sales spikes, likely due to seasonal shopping trends.
* Most orders were placed on **Tuesdays** and **Wednesdays**.

---

## 🛠 Tools & Technologies Used

* Python (VS Code)
* Pandas for data manipulation
* Matplotlib & Seaborn for visualizations
* Jupyter Notebook (optional)
* Superstore Dataset (CSV format)

---

## ⚖️ Project Structure

```
Retail_Sales_EDA_Project/
├── Superstore_EDA.py        # Python script with data cleaning & EDA
├── superstore.csv           # Dataset
├── README.md                # Project summary and reflection
└── output_images/           # (Optional) Saved charts or logs
```

---

## ⚠️ Challenges Faced & What I Learned

### ❌ Missing Values

* `Postal Code` had a few missing values.
* ✅ **Fix**: Since they were minimal and not critical for analysis, they were skipped.

### ❌ Data Aggregation Confusion

* Understanding the purpose of `groupby()` was tricky at first.
* ✅ **Fix**: Realized it's crucial to get summarized sales across `Category`, `Region`, etc.

### ❌ Visualization Errors

* Faced import issues and `TypeError` when using `plt`.
* ✅ **Fix**: Ensured correct import: `import matplotlib.pyplot as plt`

### ❌ Month/Year Confusion

* Initially tried monthly sales without grouping by year, which caused confusion in multi-year data.
* ✅ **Fix**: Used `groupby(['Order_Year', 'Order_Month'])` for clarity.

---

## 📁 How to Run the Project

1. **Clone the repository**:

```bash
git clone https://github.com/A-iftikhar02/Sales-Analysis-EDA-Project.git
```

2. **Open the directory**:

```bash
cd Sales-Analysis-EDA-Project
```

3. **Open in VS Code**:

* Open `Sales_EDA.py`
* Run line-by-line or all at once



## 🌟 Final Thoughts

This project helped me:

* Strengthen my command of Pandas and grouping techniques
* Learn how to deal with real-world data imperfections
* Improve my data storytelling using visualizations

> 📌 This project is part of my skill-building journey in data analytics. More projects coming soon!
