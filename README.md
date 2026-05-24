# 📊 Financial Literacy in Italy: Data-Driven Analysis Using IACOFI 2023

## 📌 Project Overview

This project analyzes the determinants of financial literacy among Italian adults using the **IACOFI 2023 survey dataset** from the Bank of Italy.  
The study investigates how **demographic, educational, socioeconomic, and digital factors** influence financial knowledge, behavior, and attitudes.

The main goal is to construct a **financial literacy score** and identify the most relevant predictors using statistical analysis and machine learning techniques.

---

## 🎯 Research Objective

To investigate:

> **To what extent do demographic, educational, and digital factors explain differences in financial literacy among Italian adults?**

---

## ❓ Research Questions

- Does education level influence financial literacy?
- Are there demographic differences in financial literacy by age, gender, and region?
- Is digital financial behavior associated with higher financial literacy?
- Which factors are the strongest predictors of financial literacy?

---

## 📂 Dataset

- **Source:** Bank of Italy – IACOFI 2023 Survey
- **Format:** Cross-sectional survey data (`.dta`)
- **Population:** Italian adults aged 18–79
- **Framework:** OECD-INFE financial literacy methodology

The dataset includes:
- Demographic variables such as age, gender, and region
- Socioeconomic indicators such as education, income, and employment status
- Digital behavior variables
- Financial knowledge, behavior, and attitude questions

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Loaded the `.dta` file using `pandas`
- Replaced missing and invalid codes such as `-97`, `-98`, and `-99`
- Cleaned and filtered the relevant variables

### 2. Feature Engineering
- Constructed financial knowledge, behavior, and attitude scores
- Combined the components into an overall financial literacy score
- Created a digital finance score from online financial activity variables

### 3. Exploratory Data Analysis
- Analyzed score distributions
- Compared groups by education, gender, and age
- Examined correlations among the main variables

### 4. Statistical Modeling
- Applied multiple linear regression
- Studied the influence of key predictors
- Interpreted coefficients and model fit

### 5. Clustering Analysis
- Applied K-means clustering to identify broad financial profiles
- Used PCA and the elbow method to select the number of clusters

---

## 🧠 Financial Literacy Score Construction

The financial literacy score is based on the OECD-INFE framework and includes three dimensions:

- **Knowledge**: understanding of financial concepts
- **Behavior**: saving, budgeting, and planning habits
- **Attitudes**: mindset toward long-term financial decision-making

The final score is created by combining the relevant positive and correct responses across these dimensions.

---

## 📊 Key Variables

### Demographic Variables
- Gender (`QD1`)
- Age (`QD7`)
- Region (`QD2`)

### Socioeconomic Variables
- Education (`QD9`)
- Income (`QD13`)
- Employment status (`QD10`)

### Digital Behavior Variables
- Internet access (`QD14`)
- Online financial activity (`QP8`, `QP9`)

---

## 🧪 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```bash
.
├── data/
│   └── database_eng.dta
├── pipeline Code/
│   ├── Financial Literacy Among Italian Adults.ipynb
|   ├── figures
|   └── cleaned_financial_literacy_data.csv
├── README.md
└── report.pdf
```

---

## 📈 Main Outputs

- Data cleaning and preprocessing workflow
- Financial literacy score construction
- Exploratory visualizations
- Correlation analysis
- Regression results
- Clustering-based profiling of respondents

---

## 📌 Main Findings

The analysis suggests that:

- Education is one of the strongest predictors of financial literacy.
- Digital financial behavior is positively associated with financial literacy.
- Gender differences are relatively small.
- Regional and age-related patterns exist but are less pronounced than education effects.

---

## 🚀 Future Work

Possible extensions of this project include:
- Robustness checks using alternative scoring methods
- Separate subgroup analyses by age or region
- Additional clustering methods
- Comparison with future survey waves



---

## 📎 Reference

Bank of Italy, **IACOFI 2023 – Surveys on Financial Literacy and Digital Financial Skills in Italy**
