# 🏦 Bank Marketing Decision Tree Classifier

This project aims to predict whether a customer will subscribe to a bank term deposit based on their **demographic and behavioral data** using a **Decision Tree Classifier**.

📊 Dataset: [Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing) (UCI Machine Learning Repository)

---

## 🔍 Problem Statement

Build a decision tree model that predicts whether a customer will purchase a product or service based on:
- Age, job, marital status, and education
- Contact type and campaign information
- Previous marketing outcomes

---

## 📁 Dataset Overview

The dataset includes **13 input features** and **1 binary target variable** (`y`), where:

- `y = 'yes'`: Customer subscribed
- `y = 'no'`: Customer did not subscribe

---

## 🧠 Model Used

- `DecisionTreeClassifier` from **scikit-learn**
- `criterion='gini'`, `max_depth=8`, `min_samples_split=20`, `min_samples_leaf=10`

---

## 🔧 Project Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Missing Value & Type Checks**
4. **Encoding Categorical Features**
5. **Train-Test Split**
6. **Model Training**
7. **Performance Evaluation**
8. **Visualizations (confusion matrix, tree structure, feature importance)**
9. **Business Insights**

---

## 📈 Results

| Metric           | Value |
|------------------|--------|
| **Accuracy**     | ~XX.X% |
| **Precision (Yes)** | ~XX.X% |
| **Recall (Yes)**    | ~XX.X% |
| **Top Features**    | `duration`, `poutcome`, `contact`, etc. |

*(You can update these with actual values from your output)*

---

## 📊 Visualizations

- Confusion Matrix
- Feature Importance Bar Chart
- Decision Tree (Top Levels)
- Class-wise Performance Metrics

---

## 📦 Technologies Used

- Python 🐍
- pandas, numpy
- matplotlib, seaborn
- scikit-learn

---

## 🔗 References

- [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- [Kaggle Dataset Mirror](https://www.kaggle.com/datasets/prakharrathi25/banking-dataset-marketing-targets)

---

## 👨‍💻 Author

**Prasanna Patthi**  
Data Science Intern – *SkillCraftTechnology*  
---

## 📬 Feel free to connect!

> If you find this project useful, feel free to star ⭐ the repo 

