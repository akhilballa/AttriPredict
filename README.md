# AttriPredict 🚀  
**Predicting Employee Attrition Using Machine Learning**

AttriPredict is a machine learning project that aims to forecast whether an employee will stay with or leave a company based on various organizational and personal factors. This project was developed as part of an academic competition where the goal was to optimize a classifier using the **F1 score** — a metric ideal for handling class imbalance in binary classification.

---

## 📌 Project Objectives

- Build a predictive model to classify employee exit status (Stayed/Left).
- Understand key features influencing employee retention.
- Apply data preprocessing, feature engineering, and model selection.
- Evaluate model performance using F1 score.
- Prepare predictions for Kaggle-style submission.

---

## 🧠 Features & Techniques

- 📊 **Exploratory Data Analysis (EDA)**  
  Understand data distribution, correlations, and class balance.

- 🧹 **Data Preprocessing**  
  - Handling missing values  
  - Encoding categorical variables  
  - Scaling numeric features  

- 🛠️ **Feature Engineering**  
  Derived new features and optimized existing ones.

- 🧪 **Modeling**  
  Used classification models covered in Part 1 of the course:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  

- 🧪 **Evaluation**  
  - Confusion matrix  
  - Precision, Recall, and **F1 Score** (main evaluation metric)

---

## 🗂️ Dataset Description

| File | Description |
|------|-------------|
| `train.csv` | Training data with features and `exit_status` |
| `test.csv` | Test data without target label |
| `sample_submission.csv` | Format for submitting predictions |

### 🔑 Target Column
- `exit_status`: Categorical — `Stayed` or `Left`

### 🏷️ Feature Columns (Examples)
- `age`, `gender`, `monthly_income`, `job_satisfaction`, `work_life_balance`, `overtime`, `remote_work`, `performance_rating`, etc.

---

## 📁 Repository Structure

AttriPredict/
├── data/
│ ├── train.csv
│ ├── test.csv
│ └── sample_submission.csv
├── notebooks/
│ └── attripredict_eda_modeling.ipynb
├── src/
│ ├── preprocessing.py
│ ├── modeling.py
│ └── utils.py
├── submissions/
│ └── final_submission.csv
├── README.md
└── requirements.txt
