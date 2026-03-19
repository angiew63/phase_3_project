# Customer Churn Prediction Project

# Customer Churn Prediction Project

##  Project Overview
This project builds a machine learning model to predict customer churn based on usage behavior, account details, and service interactions.

The goal is to answer:
**Are there predictable patterns in customer behavior that indicate churn?**

---

##  Data Science Workflow

1. **Data Loading & Inspection**
   - Loaded dataset and explored structure

2. **Data Cleaning**
   - Removed irrelevant columns
   - Converted target variable to numeric

3. **Feature Engineering**
   - Created total usage and total charge features
   - Generated behavioral indicators

4. **Exploratory Data Analysis (EDA)**
   - Analyzed churn distribution
   - Identified key relationships (e.g., service calls vs churn)

5. **Data Preparation**
   - Train-test split
   - Feature scaling (applied correctly to avoid leakage)

6. **Modeling**
   - Baseline model (Dummy Classifier)
   - Logistic Regression
   - Random Forest

7. **Model Improvement**
   - Hyperparameter tuning using GridSearchCV

8. **Evaluation**
   - Used classification metrics (precision, recall, F1-score)
   - ROC-AUC used for model comparison


##  Key Findings

- High customer service calls strongly predict churn
- High usage customers are more likely to churn
- Random Forest outperformed Logistic Regression

---

##  Final Model

- Model: Random Forest (tuned)
- Metric Focus: **Recall (to capture churn cases)**
- Use case: Customer retention strategy

---

##  Repository Structure


├── data/
│ └── bigml_syriatel.csv
├── notebook/
│ └── churn_analysis.ipynb
├── README.md
