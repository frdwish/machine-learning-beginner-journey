# Machine Learning Beginner Journey

This repository contains my daily and weekly machine learning learning progress. I am following a structured plan and also studying
from the book "Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow" by O'Reilly.

The goal is to understand machine learning from the basics, build strong intuition, and implement everything through Jupyter notebooks.

---

## Week 1 — Core ML Foundations and Regression Models

### Day 1: Machine Learning Workflow Basics
- What is Machine Learning  
- Supervised vs Unsupervised  
- What are features and labels  
- How datasets are split into train and test  
- Why data leakage matters  
- Notebook included with full explanation

### Day 2: Linear Regression
- Understanding how linear regression works  
- What the model is trying to learn  
- How fit() and predict() work internally  
- Error metrics: MAE, MSE, RMSE  
- Creating and reading a scatter plot (actual vs predicted)  
- Step-by-step explanations inside the notebook

### Day 3: Polynomial & Multiple Regression, Regularization
- When linear regression is not enough (non-linear patterns)  
- Polynomial features and how they create curves  
- Multiple regression with more than one feature  
- Regularization: Ridge and Lasso (why and how)  
- Notebook included

### Day 4: Model Evaluation  
Notebook:  
`week1_core_ml_and_regression/04_Model_Evaluation.ipynb`

Topics:
- R² score  
- Residual analysis  
- Cross-validation  
- Underfitting vs overfitting  
- Model reliability  
  
### Day 5: California Housing Regression Project  
Notebook:  
`week1_core_ml_and_regression/05_California_Housing_Regression.ipynb`

Topics and steps included:
- Load dataset using `sklearn.datasets.fetch_california_housing()`  
- Basic data inspection (`.info()`, `.describe()`, missing values)  
- Exploratory Data Analysis (correlation heatmap, scatter plots)  
- Train-test split (`train_test_split`)  
- Preprocessing: `StandardScaler()` inside a `Pipeline`  
- Linear Regression training and prediction  
- Evaluation metrics: MAE, RMSE, R²  
- Residuals plot and interpretation  
- 5-fold cross-validation using `cross_val_score()`  
- Notes on next steps: feature engineering, regularized models, pipelines for production

----

## Goal of This Repository
I want to build a strong understanding of ML instead of blindly writing code. Everything here is explained in simple words for future revision.

---

## Learning Source
Hands-On Machine Learning with Scikit-Learn, Keras, and TensorFlow  
I follow the chapters and recreate the ideas in my own notebooks.

---

## Repository Structure

```
machine-learning-beginner-journey/
│── week1_core_ml_and_regression/
│   ├── 01_ML_Workflow_TrainTestSplit.ipynb
│   ├── 02_LinearRegression_DeepExplanation.ipynb
│   ├── 03_Polynomial_Regression.ipynb
│   ├── 04_Model_Evaluation.ipynb
│   ├── 05_California_Housing_Regression.ipynb
│   ├── data/   (optional, not committed)
│── README.md
```

---


> Note: Make sure filenames and folder names match your local files before pushing.

---

## How to use this repo
1. Clone the project  
2. Open the notebooks in Jupyter Notebook or VS Code  
3. Run the cells and follow the explanations  
4. Review results, save selected plots to `images/`, and update notes

---

## Datasets
- Large or private datasets should not be committed. Put them in `week1_core_ml_and_regression/data/` locally and add names to `.gitignore`.  
- For the California housing experiments, use `sklearn.datasets.fetch_california_housing()` to load data programmatically in the notebook.

---

## Updates
I will update this repository as I complete more parts of the learning plan.



---

## Updates
I will update this repository daily as I complete more parts of my learning plan.
