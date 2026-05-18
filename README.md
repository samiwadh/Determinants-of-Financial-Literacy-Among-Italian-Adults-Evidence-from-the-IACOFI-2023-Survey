# 📊 Financial Literacy in Italy: Data-Driven Analysis Using IACOFI 2023

## 📌 Project Overview

This project analyzes the determinants of financial literacy among Italian adults using the **IACOFI 2023 survey dataset**.  
The study explores how **demographic, educational, socioeconomic, and digital factors** influence financial knowledge, behavior, and attitudes.

The goal is to construct a **financial literacy score** and identify the most significant predictors using statistical and machine learning techniques.

---

## 🎯 Research Objective

To investigate:

> **To what extent do demographic, educational, and digital factors explain differences in financial literacy among Italian adults?**

---

## ❓ Sub-Questions

- Does education level influence financial literacy?
- Are there demographic differences (age, gender, region)?
- Is digital financial behavior associated with higher literacy?
- Which factors are the strongest predictors of financial literacy?

---

## 📂 Dataset

- **Source:** Bank of Italy – IACOFI 2023 Survey  
- **Type:** Cross-sectional survey data (.dta format)  
- **Population:** Italian adults  
- **Methodology:** OECD-INFE financial literacy framework  

The dataset includes:
- Demographic variables (age, gender, region, etc.)
- Socioeconomic indicators (education, income, employment)
- Digital behavior variables
- Financial knowledge, behavior, and attitude questions

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Loaded `.dta` file using `pandas`
- Handled missing values (`-97`, `-98`, `-99`)
- Cleaned and filtered relevant variables

### 2. Feature Engineering
- Constructed **Financial Knowledge Score**
- Combined correct responses from OECD-style questions
- Created structured analytical dataset

### 3. Exploratory Data Analysis (EDA)
- Distribution of financial literacy scores
- Group comparisons (education, gender, age)
- Correlation analysis

### 4. Statistical Modeling
- Multiple Linear Regression
- Analysis of feature importance
- Interpretation of coefficients

### 5. (Optional Extension)
- Clustering analysis for financial profiles

---

## 🧠 Financial Literacy Score Construction

The financial literacy score is built using OECD-INFE methodology:

- **Knowledge Component** (financial concepts understanding)
- **Behavior Component** (saving, budgeting habits)
- **Attitude Component** (financial decision mindset)

Final score = sum of correct/positive responses across components.

---

## 📊 Key Variables

### Demographic
- Gender (QD1)
- Age (QD7)
- Region (QD2)

### Socioeconomic
- Education (QD9)
- Income (QD13)
- Employment status (QD10)

### Digital Behavior
- Internet access (QD14)
- Online financial activity (QP8, QP9)

---

## 🧪 Technologies Used

- Python 🐍
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Stats & Regression Models
- Jupyter Notebook

---

## 📁 Project Structure
