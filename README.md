# Loan Repayment Risk Analysis & Data Engineering Pipeline

## 📌 Overview
This project focuses on building a **data engineering and analysis pipeline** for a fintech loan dataset.  
The goal is to **clean, preprocess, and structure raw loan application data** so it can later be used by **machine learning models** to:
- Predict the likelihood of loan repayment
- Assess credit risk
- Estimate expected repayment duration

The project emphasizes **data quality, consistency handling, and exploratory analysis**, which are critical in financial and banking systems.

---

## 🎯 Objectives
- Clean and standardize raw fintech loan data
- Handle missing, duplicated, and inconsistent values
- Engineer high-quality features for downstream ML models
- Provide statistical insights into loan repayment behavior

---

## 🧠 Dataset Description
The dataset contains information about loan applicants, including:
- Employment and income information
- Home ownership status
- Loan purpose and loan amount
- State of residence
- Credit-related attributes

> ⚠️ The dataset is preprocessed locally and is not included for privacy reasons.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data manipulation and preprocessing
- **NumPy** – numerical computations
- **Matplotlib / Seaborn** – data visualization
- **Jupyter Notebook** – interactive data analysis

---

## 🔄 Data Engineering Pipeline

### 1. Data Loading
- Loaded CSV data into Pandas DataFrame
- Verified schema and basic statistics

### 2. Data Cleaning
- Renamed all columns for consistency
- Removed duplicated records
- Standardized text data (case normalization)
- Fixed inconsistent categorical values
- Handled invalid and ambiguous entries

### 3. Missing Value Handling
- Identified missing and hidden null values
- Replaced categorical missing values using **mode**
- Ensured numerical columns were logically valid

### 4. Feature Preparation
- Prepared clean, structured features suitable for:
  - Risk classification models
  - Repayment duration prediction
  - Creditworthiness analysis

### 5. Exploratory Data Analysis (EDA)
- Analyzed income distribution and loan behavior
- Visualized correlations between applicant attributes
- Studied patterns affecting loan repayment

---

## 📊 Key Insights
- Strong relationships observed between income, loan amount, and repayment likelihood
- Data inconsistencies significantly affect model reliability if not handled
- Proper feature engineering is critical before applying ML algorithms in financial systems

---

## 📁 Project Structure
