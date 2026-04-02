<div align="center">
<!-- Animated Header Banner -->
<img width="1584" height="396" alt="Beige Modern Professional General Linkedin Banner" src="https://github.com/user-attachments/assets/74363399-4259-47ea-bafa-7496eb9f0fd7" />
<br/>
</div>

# Salary Prediction & Income Analysis

<div align="center">

![Project Banner](https://img.shields.io/badge/Data%20Science-Project-2d6a27?style=for-the-badge&logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-In%20Progress-f5a623?style=for-the-badge)
![Dataset](https://img.shields.io/badge/Dataset-UCI%20Adult%20Income-4a90d9?style=for-the-badge&logo=databricks&logoColor=white)
![ML](https://img.shields.io/badge/Machine%20Learning-Classification-2d6a27?style=for-the-badge&logo=scikitlearn&logoColor=white)

> **Can we predict whether a person earns more than $50K a year?**  
> A complete data science study analyzing income determinants using the UCI Adult Income Dataset.

---

**Course:** Fundamentals of Data Science &nbsp;|&nbsp; **Dept:** Computer Science, CADT IDT  
**Lecturer:** Ms. Sam Sreyleak &nbsp;|&nbsp; **Date:** February 20, 2026

</div>

---
<div align="center">
##  Team 1

| Name | Role |
|------|------|
| 🧑‍💻 Huy Visa | Team Member |
| 🧑‍💻 Manh Seila | Team Member |
| 🧑‍💻 Eng Mengeang | Team Member |
| 🧑‍💻 Chheang Sovanpanha | Team Member |
| 🧑‍💻 Both Chealean | Team Member |

---
</div>

## 🔍 Problem Statement

Many students and job seekers **lack clarity** on how education, skills, experience, and job roles translate into expected salaries. This transparency gap leads to:

-  Poor career decisions
-  Unrealistic salary expectations
-  Mismatch between acquired skills and market demand

>  *Only 34–36% of students are confident they will graduate with the skills needed to succeed in the job market.* — Strada Education Network (2018)

---

##  Our Solution

We develop a **salary prediction system** using data analytics and machine learning to estimate expected income levels based on key factors:

```
Education Level  →
Work Experience  →   [ ML Model ]  →  Income Class (≤$50K or >$50K)
Job Role         →
Hours per Week   →
```

This system helps individuals **make smarter, data-driven career decisions**.

---

##  Project Objectives

- [ ]  Understand income distribution patterns
- [ ]  Study how education level influences salary
- [ ]  Identify key factors affecting higher income
- [ ]  Build and compare predictive ML models
- [ ]  Generate interpretable insights for decision-making

---

## 📁 Dataset

**Source:** [UCI Machine Learning Repository — Census Income Dataset](https://archive.ics.uci.edu/dataset/20/census+income)

| Attribute | Type | Description |
|-----------|------|-------------|
| `age` | Numerical | Age of individual |
| `workclass` | Categorical | Employee type |
| `education` | Categorical | Education level |
| `education-num` | Numerical | Education encoded numerically |
| `marital-status` | Categorical | Marital status |
| `occupation` | Categorical | Job role |
| `relationship` | Categorical | Family relationship |
| `race` | Categorical | Race group |
| `sex` | Categorical | Gender |
| `capital-gain` | Numerical | Investment gains |
| `capital-loss` | Numerical | Investment losses |
| `hours-per-week` | Numerical | Working hours per week |
| `native-country` | Categorical | Country of origin |
| `income` | **Target**  | Salary class (`<=50K` or `>50K`) |

>  `fnlwgt` (sampling weight) is removed as it holds no predictive value.

---

## 🔄 Project Workflow

```
┌──────────────────────────────────────────────────────────────┐
│                       8-Step Pipeline                        │
├────────┬─────────────────────────────────────────────────────┤
│ Step 1 │ Data Understanding — inspect structure & anomalies  │
│ Step 2 │ Data Cleaning     — remove noise & fix values       │
│ Step 3 │ EDA               — visualize trends & patterns     │
│ Step 4 │ Statistical Analysis — hypothesis tests, insights   │
│ Step 5 │ Feature Engineering — encode, scale, transform      │
│ Step 6 │ ML Modeling       — train & tune classifiers        │
│ Step 7 │ Model Evaluation  — accuracy, F1, ROC, AUC          │
│ Step 8 │ Reporting         — conclusions & recommendations   │
└────────┴─────────────────────────────────────────────────────┘
```

### Step Details

<details>
<summary><strong> Step 1 — Data Understanding</strong></summary>

- Inspect dataset size, structure, and data types
- Identify missing values and anomalies
- Understand class imbalance
- Summarize numerical and categorical distributions

</details>

<details>
<summary><strong> Step 2 — Data Cleaning</strong></summary>

- Remove irrelevant attributes (`fnlwgt`)
- Handle missing or unknown values (`?`)
- Fix inconsistent categories
- Remove duplicates and outliers

</details>

<details>
<summary><strong> Step 3 — Exploratory Data Analysis</strong></summary>

- Analyze salary distribution
- Compare education level vs income
- Study occupation and workclass trends
- Visualize age and hours-per-week impacts
- Generate correlation heatmaps and boxplots

</details>

<details>
<summary><strong> Step 4 — Statistical Analysis</strong></summary>

- Group-by comparisons for income trends
- Hypothesis testing for education impact
- Measure correlations between features
- Interpret which attributes influence salary most

</details>

<details>
<summary><strong> Step 5 — Feature Engineering</strong></summary>

- Encode categorical variables (One-Hot / Label Encoding)
- Create education rank scores
- Create overtime indicator (`hours > 40`)
- Group rare categories
- Scale numeric features

</details>

<details>
<summary><strong> Step 6 — Machine Learning Modeling</strong></summary>

| Model | Purpose |
|-------|---------|
| Logistic Regression | Baseline |
| Decision Tree | Interpretability |
| Random Forest | Higher Accuracy |
| Gradient Boosting | Best Performance |

- Perform train-test split and cross-validation

</details>

<details>
<summary><strong> Step 7 — Model Evaluation</strong></summary>

- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix & ROC Curve
- Model comparison and best performer selection
- Feature importance analysis

</details>

<details>
<summary><strong> Step 8 — Reporting & Conclusion</strong></summary>

- Summarize findings and insights
- Discuss education's impact on salary
- Provide career recommendations
- Document limitations and future improvements

</details>

---

## Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C8CBF?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)

---

## Out of Scope

The following are **not** covered in this project:
- API Development
- Web Application
- Model Deployment
> *Scope ends at model evaluation and reporting.*
---

## References

1. **UCI Machine Learning Repository** — [Census Income Dataset](https://archive.ics.uci.edu/dataset/20/census+income)
2. **Z. Scherer & M. D. King** — *How Education Impacted Income and Earnings From 2004 to 2024*, U.S. Census Bureau, Sept. 2025
3. **Strada Education Network** — *Crisis of Confidence: Strada Student Perspectives Survey 2018*, 2018
4. **M. Xu** — *Salary prediction using machine learning*, Scholarly Review Journal, Jun. 2025. [DOI: 10.70121/001c.139043](https://doi.org/10.70121/001c.139043)

---

<div align="center">

Made with by **Team 1** · CADT Institute of Digital Technology · 2026

</div>
>>>>>>> fa72e47e6f05b1027e02135a3b60a3ebe9547ec7
