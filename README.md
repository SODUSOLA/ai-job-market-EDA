# AI Job Market Exploratory Data Analysis (EDA)

## Project Overview

This project performs an **exploratory data analysis (EDA)** on a publicly available **AI job market dataset** using **Python and Pandas**.  
The goal is to explore the structure of the data, compute descriptive statistics, and identify relationships between key numerical features such as salary, experience level, remote work ratio, and benefits.

---

## Dataset Description

The dataset contains **15,000 AI-related job postings** with information including:

- Job title and company
- Salary (USD)
- Years of experience required
- Remote work ratio
- Job description length
- Benefits score
- Company location and si

The dataset is clean, with **no missing values**, making it suitable for exploratory analysis.

---

## Tools & Libraries Used

- **Python**
- **Pandas**
- **Jupyter Notebook**

---

## Analysis Performed

### 1. Data Exploration

- Displayed the first few rows using `data.head()`
- Inspected dataset structure and data types using `data.info()`
- Generated summary statistics using `data.describe()`

### 2. Basic Statistical Analysis

For all numerical features:

- Calculated **mean**
- Calculated **median**
- Calculated **mode**
- Calculated **standard deviation**

### 3. Correlation Analysis

- Computed the correlation matrix using `data.corr()`
- Analyzed relationships between salary, experience, remote work ratio, and benefits

---

## Key Insights

- **Years of experience** has a strong positive correlation with **salary**
- **Remote work ratio** shows little to no correlation with salary
- AI roles generally offer **high benefits scores**
- Salary distribution is **right-skewed**, with a few very high-paying roles

---
