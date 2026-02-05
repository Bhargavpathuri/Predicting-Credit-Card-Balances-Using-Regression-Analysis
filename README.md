# Predicting Credit Card Balances Using Regression Analysis

## 📌 Project Overview

This project focuses on building statistical models to predict individuals’ credit card balances using demographic and financial variables. The analysis was conducted as part of a **Regression Analysis** course and was completed by a team of four members.

The goal of this project is to identify key drivers of credit card usage and evaluate predictive performance using regression modeling techniques.

---

## 📊 Dataset

The dataset used in this project is **Credit.csv**, obtained from the ISLR dataset collection. It contains demographic and financial information used to study credit behavior.

### Key Variables

* **Response Variable**

  * `Balance` – Average credit card balance

* **Predictor Variables**

  * Income
  * Credit Limit
  * Rating
  * Age
  * Education
  * Number of Cards
  * Gender
  * Student Status
  * Marital Status
  * Ethnicity

---

## ⚙️ Methodology

### 1. Data Preprocessing

* Data cleaning and missing value checks
* Feature engineering (log transformation of predictors)

### 2. Exploratory Data Analysis (EDA)

* Scatterplot matrices
* Correlation analysis
* Boxplots and histograms
* Identification of outliers and influential points

### 3. Model Development

* Multiple Linear Regression
* Feature transformations (log transformation, Box-Cox analysis)
* Multicollinearity checks (VIF)
* Interaction term modeling

### 4. Model Selection & Validation

* AIC/BIC model selection
* 10-fold cross-validation
* Residual diagnostics
* Cook’s distance and leverage analysis

---

## 📈 Final Model

The final regression model included:

```
Balance ~ log(Income) + log(Limit) + Student + log(Limit):Student
```

### Key Findings

* Credit limit is the strongest predictor of credit card balance.
* Higher income is associated with lower credit card debt.
* Student status significantly impacts borrowing behavior.
* Interaction between credit limit and student status improves model performance.

The final model explained approximately **94% of the variation** in credit card balances.

---

## 🧰 Tools & Technologies

* Python / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib / Seaborn
* Statsmodels / Regression Analysis

---

## 📂 Repository Structure

```
├── Credit.csv                        # Dataset
├── STAT611_Project_Final.ipynb       # Analysis and modeling code
├── STAT611_Project_Final_Report.pdf  # Detailed project report
└── README.md                         # Project documentation
```

---

## 👥 Team Contributions

* **Data Cleaning & Feature Engineering**
* **Exploratory Data Analysis**
* **Model Diagnostics & Validation**
* **Model Selection and Interpretation**

---

## 🚀 How to Run the Project

1. Clone the repository
2. Install required libraries
3. Open the Jupyter Notebook
4. Run all cells to reproduce analysis

---

## 📄 Project Report

The complete methodology, results, and statistical interpretation are documented in the project report:


---

## 📚 Learning Outcomes

* Applied regression modeling to real-world financial data
* Practiced statistical diagnostics and model validation
* Interpreted interaction effects in predictive models
* Strengthened data visualization and exploratory analysis skills



Just tell me 👍
