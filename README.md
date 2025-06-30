# 📊 Task 5: Exploratory Data Analysis (EDA) – Titanic Dataset

Welcome to Task 5 of my Data Analyst Internship! This task focuses on using Python to perform a complete exploratory data analysis on the iconic Titanic dataset, uncovering patterns that influenced passenger survival.

---

## 🎯 Objective

The goal is to extract meaningful insights from the Titanic dataset using Python libraries like Pandas, Matplotlib, and Seaborn. This includes analyzing missing data, identifying trends, and visualizing survival rates based on different passenger features.

---

## 🧰 Tools & Libraries Used

- Python 🐍
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

---

## 📦 Dataset Info

- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
- **File Used:** `train.csv`
- **Total Rows:** 891
- **Columns:** 12 (including Survived, Pclass, Sex, Age, Fare, Embarked, etc.)

---

## 📁 Project Structure

Task5_EDA_Titanic/
├── titanic_eda.ipynb # 🔍 Jupyter Notebook with all EDA code
├── titanic_eda.pdf # 📄 Exported PDF report with insights (optional)
├── train.csv # 📦 Dataset file used
└── README.md # 📘 This file

---

## 🔍 Key Steps Performed

- ✅ Loaded and cleaned Titanic dataset
- ✅ Identified missing values and filled them appropriately
- ✅ Generated summary statistics
- ✅ Created meaningful visualizations:
  - Countplot of survival vs gender
  - Boxplot of age vs passenger class
  - Heatmap of feature correlations
  - Histogram of fare and age
  - Pairplot for multivariate relationships
- ✅ Analyzed patterns and wrote insight summaries

---

## 📊 Visual Highlights

### Gender vs Survival
Female passengers had a much higher survival rate than males.

### Class vs Survival
1st class passengers had the highest survival rate, 3rd class the lowest.

### Age & Fare
- Younger passengers had slightly higher chances of survival.
- Higher fare = higher survival likelihood.

---

## 🧠 Insights Summary

- **Gender:** 75% of females survived vs 19% of males.
- **Class:** 63% of 1st class passengers survived.
- **Embarked Port:** Port 'C' had highest survival percentage.
- **Fare:** Survivors paid higher fares on average.
- **Family Size:** Passengers with small families had better survival chances than those alone.

---

## 🏁 Conclusion

This EDA revealed clear survival patterns based on socio-economic status, gender, age, and fare. These insights can serve as a base for building predictive models using machine learning.

---

## 🙌 Final Thoughts

This task strengthened my understanding of data wrangling, statistical analysis, and visual storytelling using Python. It's a reminder that behind every dataset is a human story — and the Titanic dataset tells one of the most historic.

---
