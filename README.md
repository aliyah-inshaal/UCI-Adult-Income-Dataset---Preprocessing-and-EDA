# UCI Adult Income Dataset — Data Cleaning & Exploratory Data Analysis

## 📌 Overview

This project performs a complete **data preprocessing and exploratory data analysis (EDA)** workflow on the **UCI Adult Income Dataset**.

The goal is to transform raw demographic and employment data into a clean, structured dataset while identifying patterns and relationships between personal attributes and income levels.

This project demonstrates essential Data Science skills including data cleaning, feature analysis, visualization, and preprocessing techniques required before building machine learning models.


## Dataset

**Dataset:** UCI Adult Income Dataset

The dataset contains information about individuals based on demographic and employment attributes. The target variable is income classification:

- `<=50K`
- `>50K`

### Features

- Age
- Work Class
- Education
- Education Number
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours per Week
- Native Country
- Income


# Project Workflow

## 1. Data Loading & Understanding

- Imported the dataset using Pandas.
- Assigned meaningful column names.
- Examined:
  - Dataset shape
  - Data types
  - Statistical summaries
  - Feature distributions


## 2. Data Cleaning

The following preprocessing steps were performed:

### Missing Value Handling

- Identified missing values represented as `"?"`.
- Converted them into proper missing values.
- Analyzed missing value distribution.
- Handled missing categorical values.

### Data Standardization

- Removed unnecessary spaces from categorical values.
- Checked unique categories before and after cleaning.
- Ensured consistent formatting across features.

### Duplicate Detection

- Identified duplicate records.
- Removed exact duplicate rows to improve data quality.


# 📊 Exploratory Data Analysis

EDA was performed to understand the relationship between demographic factors and income.

Analysis includes:

### Income Distribution

- Examined the distribution of income classes.
- Identified class imbalance between income categories.

### Age Analysis

- Studied age distribution.
- Analyzed relationship between age and income.

### Education Analysis

- Explored how education level affects income groups.

### Occupation Analysis

- Compared income distribution across different occupations.

### Working Hours Analysis

- Investigated the relationship between weekly working hours and income.

### Numerical Feature Analysis

Performed:

- Distribution analysis
- Boxplots
- Correlation analysis
- Outlier investigation

# ⚙️ Data Preprocessing Pipeline

A machine-learning-ready preprocessing pipeline was created using Scikit-learn.

### Numerical Features

Applied:

- Missing value imputation
- Feature scaling

### Categorical Features

Applied:

- Missing value handling
- One-hot encoding

Implemented using:

- `Pipeline`
- `ColumnTransformer`

This ensures consistent preprocessing for future machine learning models.


# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Visualization |
| Seaborn | Statistical plots |
| Scikit-learn | Data preprocessing |

# 📈 Key Insights

- Income distribution is highly imbalanced, with fewer individuals belonging to the higher income category.
- Education level shows a strong relationship with income.
- Certain occupations have higher representation in the higher income group.
- Capital gain and capital loss contain highly skewed values.
- Proper preprocessing is necessary before applying machine learning algorithms.

# 📁 Repository Structure

├── adult_income_data_cleaning_and_eda.ipynb
├── README.md
└── adult.csv


Data Science | Machine Learning | Artificial Intelligence
