# Salifort Motors – Employee Churn Prediction Project

## Overview

Salifort Motors is experiencing a high rate of employee turnover, which incurs significant costs in recruiting, onboarding, and training. This project aims to use data analysis and machine learning to identify factors contributing to employee churn and build models to predict which employees are most likely to leave.

Following the **PACE framework** (Plan, Analyze, Construct, Execute), this project combines exploratory data analysis, statistical modeling, and machine learning to deliver actionable insights for the HR and leadership teams at Salifort Motors.

---

## Objectives

- Predict whether an employee is likely to leave the company
- Identify key features contributing to turnover
- Recommend strategic actions to improve employee retention

---

## Models Built

We explored multiple approaches:

### 1. **Logistic Regression**
- Baseline model to understand linear relationships
- Good interpretability
- Moderate performance on F1 and recall for minority (churn) class

### 2. **Decision Tree**
- Nonlinear model capable of capturing complex interactions
- Easy to visualize and explain
- Slightly better recall than logistic regression

### 3. **Random Forest**
- Ensemble model that significantly improves predictive accuracy

---

## Key Insights

- Employees with **high evaluation scores** but **excessive working hours** are more likely to leave.
- **Tenure around 4 years** marks a critical point for dissatisfaction.
- **Low salary** and **no promotion in the last 5 years** are correlated with higher churn.
- **Overworked** employees (high monthly hours) are at risk, especially when not appropriately recognized.

---

## Recommendations

Based on the analysis and models:

- **Limit the number of concurrent projects** an employee handles.
- Investigate why **4-year-tenured employees** are more dissatisfied—consider timely promotions or recognition.
- **Reward longer hours** fairly and make overtime policies more transparent.
- Create **open communication forums** to address work culture and expectations.
- Ensure **high evaluation scores are not only tied to extreme work hours**; promote balance and proportional rewards.

---

## Tools & Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Jupyter Notebook
- Logistic Regression, Decision Tree, Random Forest
- GridSearchCV for hyperparameter tuning
- Classification metrics: Accuracy, Precision, Recall, F1, ROC AUC

---

## Project File Summary

| Notebook | Description |
|----------|-------------|
| `Salifort Motors Project.ipynb` | Complete end-to-end workflow with all models and visualizations |

---

## 📈 Outcome

This project demonstrates how data-driven modeling can improve decision-making in human resources. The models provide predictive power and interpretability, allowing stakeholders to identify at-risk employees and take proactive steps to improve retention and reduce costs.

