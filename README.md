# 🏦 Banking Customer Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)
![MySQL](https://img.shields.io/badge/MySQL-Database-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

## 📌 Overview

This project performs **Exploratory Data Analysis (EDA)** on a banking customer dataset stored in a MySQL database.

The objective is to uncover **customer behavior patterns, financial trends, and relationships between key banking variables** using Python-based data analysis and visualization techniques.

---

## 🎯 Objectives

* Analyze customer demographics and financial attributes
* Segment customers based on income levels
* Identify patterns across occupations, nationality, and banking behavior
* Explore correlations between financial indicators

---

## 🛠️ Tech Stack

| Category    | Tools                              |
| ----------- | ---------------------------------- |
| Language    | Python                             |
| Database    | MySQL                              |
| Libraries   | Pandas, NumPy, Matplotlib, Seaborn |
| Environment | Jupyter Notebook                   |

---

## 🗄️ Data Source

* Database: `banking_case`
* Table: `customer`
* Connection via **PyMySQL**

---

## 🔌 Database Connection

```python
cnx = pymysql.connect(
    host="127.0.0.1",
    user="root",
    password="*****",
    database="banking_case"
)
```

---

## 📊 Project Workflow

### 1️⃣ Data Extraction

* Data fetched from MySQL using SQL queries
* Loaded into Pandas DataFrame

---

### 2️⃣ Data Understanding

* Shape, structure, and summary statistics
* Data type validation and cleaning

---

### 3️⃣ Feature Engineering

Created **Income Band**:

* 🟢 Low (<100K)
* 🟡 Medium (100K–300K)
* 🔴 High (>300K)

---

### 4️⃣ Exploratory Data Analysis

#### 📌 Categorical Analysis

* Gender distribution
* Occupation insights
* Nationality trends
* Loyalty classification

#### 📌 Univariate Analysis

* Histograms
* Count plots

#### 📌 Bivariate Analysis

* Comparison across nationality
* Category relationships

---

## 📸 Visualizations

### 🔹 Income Band Distribution

![Income Band Chart](images/income_band.png)

### 🔹 Customer Category Distribution

![Categorical Analysis](images/categorical_plot.png)

### 🔹 Numerical Feature Distribution

![Histogram](images/numerical_distribution.png)

### 🔹 Correlation Heatmap

![Heatmap](images/heatmap.png)

> 📁 **Note:** Add your screenshots to a folder named `images/` in your repository.

---

## 📈 Key Insights

* Customers are concentrated in specific income bands
* Strong relationships exist between:

  * 💳 Credit Card Balance & Bank Loans
  * 💰 Deposits & Savings Accounts
* Certain occupations show higher financial activity
* Nationality influences product usage patterns

---

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/banking-analysis.git
cd banking-analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn pymysql
```

### 3. Setup Database

* Ensure MySQL is running
* Create database: `banking_case`
* Import `customer` table

### 4. Run the Notebook

```bash
jupyter notebook
```

---

## 📂 Project Structure

```
banking-analysis/
│
├── data/                 # (Optional) raw datasets
├── images/               # Screenshots for README
├── notebooks/            # Jupyter notebooks
├── src/                  # Python scripts
├── README.md
└── requirements.txt
```

---

## ⚠️ Important Notes

* Do NOT expose your real database password
* Replace credentials with environment variables
* Ensure proper data cleaning before analysis

---

## 🚀 Future Enhancements

* 🔮 Customer segmentation using Machine Learning
* 📊 Interactive dashboards (Power BI / Tableau)
* ⚙️ Automated data pipeline

---

## 👨‍💻 Author

**Jose Antony**
Business Analyst | Data Enthusiast

📫 Connect with me on LinkedIn *(www.linkedin.com/in/joseantonytharu)*

---

## ⭐ If you found this useful

Give this repo a ⭐ and share your feedback!

---
