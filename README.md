# customer_behavior_analysis
data analytics project showcasing customer behavior analysis using python, sql and power Bi.

# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from loading raw data in Python and performing Exploratory Data Analysis (EDA) to data cleaning, SQL analysis, Power BI dashboard development, reporting, and presentation creation.

The main objective is to transform raw data into **meaningful insights and business-ready visualizations** that can support data-driven decision-making.

---

## 🎯 Project Objectives

* Load and understand the dataset using Python
* Perform Exploratory Data Analysis (EDA)
* Clean and preprocess the data
* Analyze data using SQL
* Create meaningful business insights
* Build an interactive Power BI dashboard
* Prepare a detailed project report
* Create a professional project presentation using Gamma

---

## 📁 Dataset

The project uses a structured dataset containing relevant business/customer/transaction information.

The dataset was initially loaded into Python for:

* Understanding data structure
* Checking data types
* Identifying missing values
* Finding duplicate records
* Detecting inconsistent or incorrect values
* Understanding distributions and relationships between columns

> **Dataset:** Add your dataset name or source here.

---

## 🛠️ Tools & Technologies

| Tool                     | Purpose                               |
| ------------------------ | ------------------------------------- |
| **Python**               | Data loading, cleaning and analysis   |
| **Pandas**               | Data manipulation and preprocessing   |
| **NumPy**                | Numerical operations                  |
| **Matplotlib / Seaborn** | Data visualization and EDA            |
| **PostgreSQL**           | SQL-based data analysis               |
| **MySQL**                | SQL querying and analysis             |
| **SQL Server**           | SQL querying and analysis             |
| **Power BI**             | Interactive dashboard creation        |
| **Gamma**                | Project presentation (PPT)            |
| **Microsoft Excel**      | Supporting data analysis, if required |

---

## 🔄 Project Workflow

```text
Raw Dataset
     ↓
Load Data using Python
     ↓
Exploratory Data Analysis (EDA)
     ↓
Data Cleaning & Preprocessing
     ↓
SQL Analysis
     ↓
Business Insights
     ↓
Power BI Dashboard
     ↓
Project Report
     ↓
Gamma Presentation
```

---

## 🔹 Steps Performed

### 1. Load Dataset in Python

The dataset was imported using Pandas and examined to understand its structure.

Key activities:

* Import dataset
* Check number of rows and columns
* Inspect column names
* Check data types
* Generate basic statistical summaries

Example:

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
print(df.info())
print(df.describe())
```

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand patterns, trends, and relationships within the data.

Activities included:

* Univariate analysis
* Bivariate analysis
* Statistical summaries
* Distribution analysis
* Correlation analysis
* Visualization of important variables

Example:

```python
df.describe()
df.isnull().sum()
df.duplicated().sum()
```

---

### 3. Data Cleaning

The raw dataset was cleaned before performing further analysis.

Major cleaning activities:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Handling inconsistent values
* Removing unnecessary columns
* Checking invalid or abnormal records

The cleaned dataset was then prepared for SQL analysis and Power BI visualization.

---

### 4. SQL Analysis

The cleaned data was analyzed using SQL databases such as **PostgreSQL, MySQL, and SQL Server**.

SQL concepts used include:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `HAVING`
* `ORDER BY`
* Aggregate Functions
* `CASE` Statements
* `JOIN`
* Subqueries
* CTEs
* Window Functions

Example:

```sql
SELECT 
    category,
    COUNT(*) AS total_records,
    SUM(sales) AS total_sales
FROM orders
GROUP BY category
ORDER BY total_sales DESC;
```

SQL analysis was used to identify important trends, patterns, and business insights from the dataset.

---

## 📊 Power BI Dashboard

An interactive dashboard was created using **Power BI** to present the key findings visually.

### Dashboard Features

* KPI cards
* Interactive charts
* Bar and column charts
* Line charts
* Tables and matrices
* Filters and slicers
* Category-wise analysis
* Trend analysis
* Business performance indicators

The dashboard allows users to interact with the data and quickly understand important metrics and trends.

> **Dashboard Screenshot:** Add your Power BI dashboard screenshot here.

---

## 📈 Results & Insights

The analysis helped identify important patterns and trends from the dataset.

Key outcomes include:

* Identified important business trends
* Analyzed category-wise performance
* Identified high and low performing segments
* Examined customer/transaction patterns
* Used SQL to answer business questions
* Converted analytical findings into interactive Power BI visuals

> Add **3–5 specific insights from your actual project** here. Avoid generic statements when presenting the project to recruiters.

---

## 📄 Project Report

A detailed project report was prepared covering:

1. Introduction
2. Business Problem
3. Dataset Description
4. Data Cleaning
5. Exploratory Data Analysis
6. SQL Analysis
7. Power BI Dashboard
8. Key Insights
9. Conclusion

---

## 🖥️ Project Presentation

A professional presentation was created using **Gamma** to communicate the project workflow, analysis, dashboard, and findings.

The presentation covers:

* Project Overview
* Problem Statement
* Dataset
* Data Cleaning
* EDA
* SQL Analysis
* Power BI Dashboard
* Key Insights
* Conclusion

---

## 🚀 How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/your-username/your-repository-name.git
```

### Step 2: Navigate to the Project Folder

```bash
cd your-repository-name
```

### Step 3: Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 4: Run the Python Analysis

Open the Jupyter Notebook or Python file:

```text
EDA.ipynb
```

Run the cells to perform data loading, EDA, and data cleaning.

### Step 5: Run SQL Analysis

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL queries provided in the SQL folder.

### Step 6: Open Power BI Dashboard

Open the Power BI file:

```text
Dashboard.pbix
```

Refresh the data if required.

---

## 📂 Project Structure

```text
Data-Analytics-Project/
│
├── Dataset/
│   └── dataset.csv
│
├── Python/
│   └── EDA.ipynb
│
├── SQL/
│   └── analysis.sql
│
├── PowerBI/
│   └── Dashboard.pbix
│
├── Report/
│   └── Project_Report.pdf
│
├── PPT/
│   └── Project_Presentation.pdf
│
└── README.md
```

---

## 💡 Skills Demonstrated

* Python
* Pandas
* NumPy
* Exploratory Data Analysis
* Data Cleaning
* Data Visualization
* SQL
* PostgreSQL
* MySQL
* SQL Server
* Power BI
* Business Intelligence
* Data Storytelling
* Report Writing
* Presentation Skills

---

## 👨‍💻 Author

**Kunal Bavaskar**

B.Tech Computer Engineering | Data Analytics & Data Science

**Skills:** Python | SQL | Power BI | Tableau | Excel | Data Analytics

---

## ⭐ Conclusion

This project demonstrates a complete **end-to-end data analytics process**, from raw data preparation and analysis to SQL querying, interactive dashboard development, reporting, and presentation.

The project showcases how data can be transformed into **actionable insights through Python, SQL, and Power BI**.
