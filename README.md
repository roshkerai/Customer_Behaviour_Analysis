# 📊 Retail Customer Shopping Behavior – Data Analytics Project

## 📌 Overview
This project analyzes customer shopping behavior for a retail company using data analytics techniques. The objective is to extract actionable insights from transactional data, identify purchasing patterns, and support business decision-making through SQL analysis and interactive Power BI dashboards.

The project follows an end-to-end workflow including data cleaning, exploratory data analysis (EDA), SQL-based querying, and dashboard development.

---

## 📁 Dataset
The dataset represents retail customer purchase behavior and includes:

- Customer ID and demographics (if available)
- Product categories
- Purchase transactions
- Quantity and unit price
- Purchase date
- Total spending

This data is used to understand customer behavior, sales performance, and product trends.

---

## 🛠 Tools & Technologies
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- MySQL (SQL queries for analysis)
- Power BI (Interactive dashboard creation)
- Jupyter Notebook (EDA & cleaning)
- Excel (Optional data preview)

---

## 🔄 Project Workflow

### 1. Data Loading
- Loaded dataset using Pandas
- Performed initial inspection using `.head()`, `.info()`, and `.describe()`

### 2. Data Cleaning
- Removed duplicates
- Handled missing values
- Standardized column names
- Converted date columns to datetime format
- Created new feature: `total_spent = quantity * unit_price`

---

### 3. Exploratory Data Analysis (EDA)
- Analyzed overall sales performance
- Identified top-selling product categories
- Evaluated monthly sales trends
- Found top customers by revenue contribution
- Visualized patterns using Seaborn and Matplotlib

---

### 4. SQL Analysis (MySQL)
Key queries performed:
- Total sales calculation
- Category-wise revenue analysis
- Monthly sales trends
- Top customers by spending
- Purchase frequency analysis

---

### 5. Power BI Dashboard
An interactive dashboard was created with:

- Sales performance overview (KPIs)
- Monthly revenue trends (line chart)
- Category-wise sales distribution (bar chart)
- Top customers analysis (table)
- Dynamic filters (date, category, customer)

---

### 6. Reporting
- Summarized insights from analysis
- Highlighted business recommendations
- Identified opportunities for marketing and inventory optimization

---

## 📊 Key Insights
- Certain product categories generated the highest revenue
- A small group of customers contributed significantly to total sales
- Seasonal trends were observed in purchase behavior
- Repeat customers showed higher lifetime value
- Data supports targeted marketing and stock optimization strategies

---

## 📂 Project Structure
```bash
Retail-Customer-Analysis/
│
├── data/
│   └── retail_data.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── sql/
│   └── queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── outputs/
│   └── cleaned_retail_data.csv
│
└── README.md
