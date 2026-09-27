WEEKLY ASSESSMENT 2

Successfully completed my second weekly assessment 
# Indian Startup Funding Analysis — Pandas & EDA

## 📌 Project Overview

This project focuses on analyzing Indian startup funding data using **Python, Pandas, and NumPy**.

The dataset contains funding records of Indian startups with intentionally messy data, including inconsistent city names, industry variations, funding-stage formats, currency strings, missing values, duplicate records, and different date formats.

The main goal of this project is to clean the raw dataset and extract meaningful business insights through **Exploratory Data Analysis (EDA)**.

---

## 🎯 Objectives

The project covers:

- Data loading and inspection
- Data cleaning and preprocessing
- Handling missing values
- Removing duplicate records
- Standardizing categorical values
- Converting funding amounts into numeric values
- Converting funding dates into datetime format
- Filtering and sorting data
- Creating derived columns
- GroupBy and aggregation
- Cross-tabulation
- Exploratory analysis of startup funding patterns

---

## 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Google Colab / Jupyter Notebook**

---

## 📂 Dataset

The dataset used in this project is:

`indian_startups_funding.csv`

It contains funding records of Indian startups across different:

- Cities
- Industries
- Funding stages
- Funding amounts
- Funding dates
- Investors
- Founded years

---

## 🧹 Data Cleaning

The raw dataset required several preprocessing steps before analysis.

### Column Standardization

The columns were renamed to:

```text
startup_name
city
industry
funding_stage
amount
funding_date
investors
founded_year

