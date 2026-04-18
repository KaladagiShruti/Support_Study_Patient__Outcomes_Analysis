# US Medical Patient Outcomes — SUPPORT Study Analysis

> **MSc Data Science | Kingston University | Applied Data Programming**
> Group project — team of 4 | My contributions: data cleaning & preprocessing, EDA (univariate, bivariate, multivariate analysis), missing value imputation, feature engineering

---

## Overview

An in-depth exploratory data analysis of the **SUPPORT2 clinical dataset** (Study to Understand Prognoses and Preferences for Outcomes and Risks of Treatment) — a landmark US medical study examining patient outcomes, survival, treatment preferences and hospital costs for seriously ill hospitalised adults.

---

## Dataset

**SUPPORT2** — 9,105 patient records × 48 features  
Variables: clinical measurements (vital signs, lab results), demographics (age, sex, race), outcomes (survival, death, hospital charges), treatment decisions (DNR status, care preferences)  
Source: UCI Machine Learning Repository | Creator: Frank Harrell, Vanderbilt University  
Link: https://archive.ics.uci.edu/dataset/880/support2

---

## Tools & Technologies

- Python 3
- pandas, NumPy
- Matplotlib, Seaborn
- SciPy, statsmodels, scikit-learn
- Jupyter Notebook

---

## Data Preprocessing

- Loaded and inspected 9,105 patient records across 48 features
- Performed comprehensive **missing value analysis** — identified variables with high missingness and applied appropriate imputation strategies
- Removed irrelevant columns (e.g. Patient_ID — technical identifier only)
- **Converted categorical variables** (sex, race, DNR status, disease group) to proper categorical dtype
- **Fixed data types** — ensured numerical clinical variables stored as float/int, categorical as category
- Applied **age binning** — grouped continuous age into discrete demographic categories for pattern analysis
- Standardised column names for consistency

---

## Analysis Structure

### Univariate Analysis
- Clinical numerical variables: distribution shapes, outliers, ranges for vital signs and lab results
- Demographic findings: slight male predominance (56.3% male, 43.7% female)
- Distribution summaries for all 48 variables

### Bivariate Analysis
- **Numerical vs Numerical**: correlation analysis between clinical variables
- **Categorical vs Numerical**: hospital charges vs DNR status — DNR decisions directly influence treatment intensity and costs
- Clinically relevant pairwise relationships across patient outcomes

### Multivariate Analysis
- **Correlation matrix** — identified key relationships across clinical, demographic, and outcome variables
- Multi-dimensional pattern analysis combining disease group, age band, and survival outcomes
- Statistical tests applied: Mann-Whitney U, Chi-squared, Kruskal-Wallis, ANOVA

### Research Questions & Analytical Objectives
- Survival and mortality patterns across disease categories
- Relationship between clinical severity scores and hospital charges
- Impact of DNR status and care preferences on treatment outcomes
- Demographic disparities in patient outcomes

---

## My Contributions

- Led **data cleaning and preprocessing pipeline** — missing value handling, data type corrections, column standardisation
- Performed **missing value imputation** strategy selection per variable type
- Implemented **age binning** for demographic segmentation
- Conducted **univariate EDA** — distribution analysis for all clinical numerical and categorical variables
- Contributed to **bivariate and multivariate analysis** — correlation matrix, categorical vs numerical comparisons
- Documented findings with clinical interpretation for each analysis section

---

MSc Data Science, Kingston University, London
