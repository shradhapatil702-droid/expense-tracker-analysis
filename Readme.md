# Expense Tracker Data Analysis

## Overview
The **Expense Tracker Data Analysis** project focuses on analyzing personal financial transaction data to uncover spending patterns, income trends, and overall financial behavior. The project applies data cleaning, exploratory data analysis (EDA), and visualization techniques to generate meaningful financial insights.

---

## Objectives
- Analyze transaction records to evaluate income and expense trends  
- Identify high-impact spending categories  
- Study monthly financial behavior  
- Generate visual reports for better financial understanding  
- Establish a structured pipeline for financial data analysis  

---

## Dataset Description
The dataset consists of financial transaction records with the following attributes:

| Column | Description |
|----------|----------------|
| Date | Transaction timestamp |
| Account | Payment source or account used |
| Category | Type of transaction |
| Income/Expense | Indicates transaction type |
| Amount | Monetary value of transaction |
| Currency | Transaction currency |
| Note | Additional transaction details |

---

## Data Preprocessing
The following preprocessing steps were performed to ensure data quality:

- Removed duplicate and redundant columns  
- Converted `Date` column to datetime format  
- Converted `Amount` column to numeric format  
- Handled missing or inconsistent values  
- Standardized dataset structure for analysis  

---

## Exploratory Data Analysis

### 1. Income vs Expense Analysis
Evaluated the proportion of income and expense transactions to understand financial balance.

### 2. Category-wise Expense Analysis
Identified major expense contributors and spending concentration across categories.

### 3. Monthly Financial Trends
Analyzed time-based spending and income behavior to identify patterns and variations.

### 4. High-Value Transaction Analysis
Highlighted transactions that contribute significantly to total expenses.

### 5. Expense Distribution Analysis
Studied frequency and spread of expense values using statistical visualization.

---

## Visualizations
The project includes the following visual representations:

- Income vs Expense Distribution (Pie Chart)  
- Category-wise Expense Comparison (Bar Chart)  
- Monthly Expense Trend (Line Chart)    
- Top Expense Transactions  
- Expense Amount Distribution (Histogram)  

---

## Key Insights
- Expense transactions occur more frequently than income transactions  
- Food-related expenses represent a significant portion of total spending  
- Income is primarily derived from personal and family sources  
- A small number of high-value transactions heavily influence total expenditure  
- Monthly spending patterns show noticeable fluctuations  

---

## Technology Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, Matplotlib  
- **Development Environment:** Jupyter Notebook  
- **Dashboard Framework:** Streamlit  

---

## Project Structure
```
Expense-Tracker
│
├── data
│   ├── raw_expenses.csv
│   └── expenses_clean.csv
│
├── notebooks
│   ├── 01_data_cleaning.ipynb
│   └── 02_eda.ipynb
│
├── images
│   ├── category_expense.png
│   ├── expense_distribution.png
│   ├── income_vs_expense.png
│   ├── monthly_expense.png
│   └── top5_expense.png
│
├── requirements.txt
└── README.md
```

---

## Installation & Usage

### Clone Repository
```
git clone <repository-url>
cd Expense-Tracker
```

### Install Dependencies
```
pip install -r requirements.txt
```

### Run Data Analysis
Open and execute the notebook:
```
notebooks/expense_analysis.ipynb
```

### Run Dashboard
```
streamlit run app/dashboard.py
```

---

## Future Enhancements
- Interactive dashboard with advanced filtering  
- Budget tracking and financial goal monitoring  
- Machine learning-based expense forecasting  
- Multi-user and multi-currency support  

---

## Author
Shraddha Patil  
Aspiring Data Scientist
GitHub: https://github.com/shradhapatil702-droid