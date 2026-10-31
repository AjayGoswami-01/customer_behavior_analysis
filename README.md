# customer_behavior_analysis
Data analytics project showcasing customer behavior analysis using python, sql, and power Bi


# 📊 Data Analytics Project

## 📌 Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from raw dataset loading and data cleaning to exploratory data analysis, SQL analysis, dashboard development, reporting, and presentation.

The project combines **Python, SQL, Power BI, and Gamma** to transform raw data into meaningful business insights and actionable recommendations.

### 🎯 Project Objectives

- Load and understand the dataset using Python
- Perform **Exploratory Data Analysis (EDA)**
- Clean and preprocess the data
- Analyze data using **SQL**
- Create an interactive **Power BI dashboard**
- Generate a detailed analytical report
- Present key insights using a **Gamma presentation**

---

## 📂 Dataset

The project uses a structured dataset containing relevant business/customer/transaction-level information.

The dataset goes through several stages:

**Raw Data → Data Cleaning → EDA → SQL Analysis → Visualization → Insights**

### Data Preparation Includes

- Handling missing values
- Removing duplicate records
- Correcting data types
- Standardizing column values
- Handling inconsistent or invalid data
- Identifying and analyzing outliers
- Creating derived/required columns

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **Python** | Data loading, cleaning & EDA |
| **Pandas** | Data manipulation and preprocessing |
| **NumPy** | Numerical analysis |
| **Matplotlib / Seaborn** | Data visualization |
| **PostgreSQL / MySQL / SQL Server** | SQL-based data analysis |
| **Power BI** | Interactive dashboard & visualization |
| **Gamma** | Presentation / PPT creation |
| **Git & GitHub** | Project version control |

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Load Data using Python
     ↓
Data Cleaning & Preprocessing
     ↓
Exploratory Data Analysis (EDA)
     ↓
SQL Analysis
     ↓
Power BI Dashboard
     ↓
Business Insights & Recommendations
     ↓
Report
     ↓
Gamma Presentation
```

---

## 1️⃣ Data Loading

The dataset is loaded into Python using **Pandas**.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.shape)
print(df.info())
```

Initial analysis is performed to understand:

- Number of rows and columns
- Data types
- Missing values
- Duplicate records
- Basic statistics
- Important categorical and numerical variables

---

## 2️⃣ Exploratory Data Analysis (EDA)

EDA is performed to identify patterns, trends, relationships, and potential issues in the dataset.

### Key EDA Activities

- Univariate analysis
- Bivariate analysis
- Distribution analysis
- Correlation analysis
- Outlier detection
- Trend analysis
- Category-wise analysis

Example:

```python
df.describe()
```

Visualizations are created using **Matplotlib and Seaborn** to make important patterns easier to understand.

---

## 3️⃣ Data Cleaning

The raw dataset is cleaned before performing further analysis.

### Cleaning Steps

- Handle missing/null values
- Remove duplicate records
- Fix incorrect data types
- Standardize categorical values
- Remove invalid records
- Handle outliers where appropriate
- Create useful calculated columns

Example:

```python
df.drop_duplicates(inplace=True)

df.isnull().sum()
```

The cleaned dataset is then used for SQL analysis and dashboard development.

---

# 4️⃣ SQL Analysis

The cleaned data is analyzed using relational databases such as:

- PostgreSQL
- MySQL
- SQL Server

SQL queries are used to answer important business questions.

### SQL Analysis Includes

- Aggregations
- Filtering
- Sorting
- GROUP BY
- HAVING
- CASE statements
- Subqueries
- Joins
- Window functions
- CTEs
- Ranking and trend analysis

Example:

```sql
SELECT 
    category,
    SUM(sales) AS total_sales
FROM sales_data
GROUP BY category
ORDER BY total_sales DESC;
```

The SQL analysis helps identify important **business trends, top-performing categories, customer behavior, and performance metrics**.

---

# 5️⃣ Power BI Dashboard

An interactive **Power BI dashboard** is created to present the most important findings visually.

### Dashboard Components

- KPI Cards
- Bar Charts
- Line Charts
- Pie/Donut Charts
- Tables
- Slicers
- Filters
- Trend Analysis

### Example KPIs

- Total Sales
- Total Customers
- Total Orders
- Average Order Value
- Profit
- Growth Rate

The dashboard allows users to interactively filter and explore the data.

### 📊 Dashboard Preview

Add your Power BI dashboard screenshot here:

```markdown
![Power BI Dashboard](images/dashboard.png)
```

---

# 6️⃣ Business Insights & Results

The analysis provides meaningful insights from the dataset.

### Key Findings

- Identified the best-performing categories/products.
- Analyzed sales and performance trends over time.
- Identified high-value customers or segments.
- Compared performance across different regions/categories.
- Identified areas with lower performance.
- Used data-driven analysis to generate actionable recommendations.

> **Note:** Replace the above points with the actual findings from your project.

---

# 7️⃣ Analytical Report

A detailed report is prepared to document the complete analysis.

The report includes:

1. Project Introduction
2. Business Problem
3. Dataset Description
4. Data Cleaning Process
5. Exploratory Data Analysis
6. SQL Analysis
7. Power BI Dashboard
8. Key Insights
9. Recommendations
10. Conclusion

The report explains both the **technical process** and the **business insights** obtained from the data.

---

# 8️⃣ Gamma Presentation

A professional presentation is created using **Gamma** to communicate the project findings.

### Presentation Covers

- Business Problem
- Dataset
- Methodology
- Data Cleaning
- EDA
- SQL Analysis
- Dashboard
- Key Insights
- Recommendations
- Conclusion

Gamma is used to convert the analytical findings into a concise and visually appealing presentation.

---

# 📁 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── python/
│   └── EDA_and_Cleaning.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── analytical_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

# ▶️ How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
```

### Step 2: Navigate to the Project

```bash
cd data-analytics-project
```

### Step 3: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### Step 4: Run the Python Notebook

Open:

```text
python/EDA_and_Cleaning.ipynb
```

Run the notebook sequentially to perform data loading, cleaning, and EDA.

### Step 5: Run SQL Queries

Import the cleaned dataset into your preferred database:

- PostgreSQL
- MySQL
- SQL Server

Then execute the queries available in:

```text
sql/analysis_queries.sql
```

### Step 6: Open Power BI Dashboard

Open:

```text
powerbi/dashboard.pbix
```

Update the data source if required and refresh the dashboard.

---

# 💡 Key Skills Demonstrated

This project demonstrates practical knowledge of:

- Data Cleaning
- Exploratory Data Analysis
- Python & Pandas
- SQL
- Database Analysis
- Data Visualization
- Power BI
- Dashboard Development
- Business Intelligence
- Data Storytelling
- Report Writing
- Presentation Development

---

# 🎯 Conclusion

This project demonstrates a complete **end-to-end data analytics workflow**, from raw data to business insights.

By combining **Python for data preparation and EDA, SQL for analytical querying, Power BI for visualization, and Gamma for presentation**, the project shows how raw data can be transformed into meaningful information that supports data-driven decision-making.

---

## 👤 Author

**Ajay Goswami**

📌 Data Analytics | Python | SQL | Power BI | Excel
