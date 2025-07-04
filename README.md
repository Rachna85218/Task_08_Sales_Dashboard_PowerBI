
# 📊 Task 08: Sales Dashboard – Power BI

A simple yet interactive Power BI dashboard project that visualizes sales performance by **Month-Year**, **Region**, and **Category** using the [Global Superstore Dataset](https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset?utm_source=chatgpt.com).

---

## 🎯 Objective

Build a clean and professional dashboard to analyze and display:
- Monthly sales trends
- Regional sales distribution
- Category-wise sales breakdown
- Key performance indicators (KPIs)

---

## 📂 Dataset

**Source:** [Global Superstore Dataset on Kaggle](https://www.kaggle.com/datasets/fatihilhan/global-superstore-dataset?utm_source=chatgpt.com)  
**File used:** `Global Superstore.csv`  
**Key columns:**
- `Order Date`
- `Region`
- `Category`
- `Sales`
- `Profit`
- `Year`

---

## 🔧 Tools Used

- 🧠 Power BI Desktop
- 🧹 Power Query (for date formatting and transformations)

---

## 🧹 Data Preprocessing Steps

- Cleaned `Order Date` column by removing time values (`00:00:00`)
- Created new `Month-Year` column using `Date.ToText()` in Power Query
- Added a `Month Index` to sort `Month-Year` chronologically
- Filtered out irrelevant columns

---

## 📊 Dashboard Features

### 1. KPI Cards
- **Total Sales**
- **Total Profit**

### 2. Line Chart
- **Sales over Time (Month-Year)**

### 3. Bar Chart
- **Sales by Region**

### 4. Donut Chart
- **Sales by Category**

### 5. Filters (Slicers)
- **Region**
- **Category**
- **Year Range Slider**

---

## ✨ Sample Insights

- 📉 Sales trend gradually declined from 2011 to 2014
- 🌍 Central region generated the highest sales
- 🪑 Furniture and Technology categories contributed over 70% of total sales
- 🎯 Q4 showed higher sales in most years

---

## 📦 Deliverables

- 📁 Power BI `.pbix` file
- 📷 Dashboard screenshot
- 📝 Word file with key business insights

---

## 👩‍💻 Author

**Rachna Verma**  
MSc Data Science Student | Data Analyst Intern  
📍 Pune, India  
🔗 [GitHub: Rachna85218](https://github.com/Rachna85218)

---


