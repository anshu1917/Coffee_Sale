# ☕ Coffee Sales Analysis Dashboard  

## 📌 Project Overview  
This is the **first project** of my **Data Analytics Internship** with **Unified Mentor**.  
The project focuses on analyzing **coffee sales data** and building an **interactive Power BI dashboard** to generate actionable business insights.  

---

## 🎯 Objectives  
- 🧹 Clean and preprocess sales data using Python  
- 🔍 Perform Exploratory Data Analysis (EDA)  
- 📊 Build visualizations to track sales & customer behavior  
- 📈 Create KPIs for decision-making  
- 🖥 Deliver a Power BI interactive dashboard  

---

## 🗂 Dataset  
- **Source:** Coffee Sales CSV file  
- **Records:** 1133 transactions  
- **Key Columns:**  
  - 📅 `Date` / `DateTime` → Transaction timestamps  
  - 💳 `Cash_Type` → Payment method (Cash / Card)  
  - 👤 `Card` → Customer ID (anonymized)  
  - 💵 `Money` → Revenue per transaction  
  - ☕ `Coffee_Name` → Product purchased  

---

## ⚙️ Steps Performed  

<details>
<summary>🔹 Data Cleaning & Preparation</summary>

- Renamed columns for clarity  
- Converted `Date` and `DateTime` to datetime format  
- Filled missing values in `Card` with `"Cash_user"`  
- Extracted new columns:  
  - `Month`  
  - `Day_of_Week`  
  - `Hour`  
- Exported cleaned dataset as **`cleaned_coffee_sales.csv`**  
</details>  

<details>
<summary>🔹 Exploratory Data Analysis (EDA)</summary>

- Revenue by coffee type  
- Monthly sales trend  
- Sales by day of week & hour of day  
- Payment method analysis (Cash vs Card)  
</details>  

<details>
<summary>🔹 Dashboard in Power BI</summary>

✨ The dashboard highlights:  

1. **KPIs (Cards)**  
   - 📌 Total Revenue  
   - 🛒 Total Transactions  
   - 👥 Unique Customers  
   - 💳 % Card Payments  

2. **Visuals**  
   - 📊 Top Selling Coffee Types (Bar Chart)  
   - 📈 Monthly Sales Trend (Line Chart)  
   - 🥧 Sales by Day of Week (Pie Chart)  
   - ⏰ Sales by Hour (Column Chart)  

3. **Interactive Filters (Slicers)**  
   - Payment Type (Cash vs Card)  
   - Coffee Type  
   - Month  
</details>  

---

## 📊 Dashboard Preview  
*(Add your dashboard screenshot here)*  

---

## 🚀 Key Insights  
- ☕ **Latte & Americano** are the most popular coffee types  
- ⏰ Sales peak during **10–12 AM (morning hours)**  
- 📅 **Tuesdays & Fridays** record the highest transactions  
- 💳 **92% of payments are via Card**  

---

## 🛠 Tools & Technologies  
- **Python** → Pandas, Matplotlib, Seaborn  
- **Power BI** → Dashboard design & visualization  
- **Excel / CSV** → Data handling  

---

## 📌 Outcome  
This project demonstrates how **Data Analytics + Visualization** can help businesses:  
✅ Track revenue & transactions  
✅ Understand customer purchase behavior  
✅ Optimize product & payment strategies  

---

