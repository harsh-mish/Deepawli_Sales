# 🪔 Diwali Sales Analysis

## 📌 Project Overview

This project focuses on analyzing Diwali sales data to understand **customer purchasing behavior, sales patterns, customer demographics, product performance, and geographic trends**.

The analysis was performed using **Python, Pandas, NumPy, Matplotlib, Seaborn, and Jupyter Notebook**. The objective is to transform raw sales data into meaningful insights that can support data-driven business decisions.

---

## 🎯 Objectives

* Analyze overall sales and order patterns
* Understand customer demographics and purchasing behavior
* Identify high-performing customer segments
* Analyze sales across different states and zones
* Identify top-performing occupations
* Analyze product categories based on sales and orders
* Explore relationships between different numerical variables
* Create meaningful visualizations for business insights

---

## 🛠️ Tech Stack

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook** – Analysis environment

---

## 📂 Dataset

The project uses the **Diwali Sales Data** dataset containing customer, demographic, geographic, order, and product-related information.

Key attributes analyzed include:

* Gender
* Age Group
* Marital Status
* Occupation
* State
* Zone
* Orders
* Amount
* Product Category
* Product ID

---

## 🔄 Data Analysis Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning & Preprocessing
     ↓
Missing Value & Duplicate Analysis
     ↓
Exploratory Data Analysis
     ↓
Customer & Sales Segmentation
     ↓
Product & Geographic Analysis
     ↓
Data Visualization
     ↓
Business Insights
```

---

## 🧹 Data Cleaning & Preprocessing

The dataset was prepared for analysis through:

* Inspection of dataset structure and data types
* Missing-value analysis
* Duplicate-record detection
* Removal of irrelevant columns
* Numeric data type validation
* Validation of sales amount values
* Outlier review for the `Amount` column

---

## 📊 Exploratory Data Analysis

### 👥 Customer Demographics

The analysis explores sales patterns across:

* Gender
* Age Groups
* Marital Status
* Occupation

Visualizations include bar charts and an **Age Group × Gender heatmap** to understand customer segments and their sales contribution.

### 🌍 Geographic Analysis

Sales performance was analyzed across:

* States
* Zones

Top-performing states were identified using aggregated sales amounts.

### 🛍️ Product Analysis

Product performance was analyzed using:

* Product Categories
* Number of Orders
* Total Sales Amount
* Top Products by Sales

This helps identify product segments contributing significantly to overall sales.

### 📈 Statistical & Relationship Analysis

Additional analysis includes:

* Purchase amount distribution
* Gender-wise purchase distribution
* Orders vs. Sales Amount relationship
* Correlation analysis of numerical variables

---

## 📉 Visualizations

The notebook includes multiple visualizations such as:

* Sales by Gender
* Sales by Age Group
* Age Group × Gender Heatmap
* Sales by Marital Status
* Top 10 Occupations by Sales
* Top 10 States by Sales
* Sales by Zone
* Top Product Categories by Sales
* Top Product Categories by Orders
* Top Products by Sales
* Purchase Amount Distribution
* Purchase Amount by Gender
* Orders vs Sales Amount
* Numerical Correlation Heatmap

---

## 💡 Key Analysis Areas

The project demonstrates how raw transactional data can be used to:

* Segment customers based on demographics
* Compare purchasing behavior across customer groups
* Identify high-performing geographic regions
* Evaluate product-category performance
* Examine relationships between orders and sales
* Present analytical findings through clear visualizations

---

## 📁 Project Structure

```text
Deepawli_Sales/
│
├── Deepawali_Sales_Analysis.ipynb
├── Diwali Sales Data 1.csv
└── README.md
```

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/harsh-mish/Deepawli_Sales.git
```

### 2. Navigate to the project directory

```bash
cd Deepawli_Sales
```

### 3. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
Deepawali_Sales_Analysis.ipynb
```

and run the cells sequentially.

---

## 🚀 Skills Demonstrated

**Python | Pandas | NumPy | Matplotlib | Seaborn | Data Cleaning | Exploratory Data Analysis | Data Visualization | Data Aggregation | Customer Segmentation | Business Analysis**

---

## 👤 Author

**Abhishek Mishra**

B.Tech Graduate | Data Analyst | Aspiring Data Engineer

GitHub: `https://github.com/harsh-mish/`

---

## ⭐ Project Purpose

This project demonstrates practical experience in taking a raw sales dataset through **data cleaning, exploratory analysis, visualization, and business-oriented interpretation** using Python.
