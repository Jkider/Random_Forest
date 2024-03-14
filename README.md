# Social_Ad_Lab

## Table of Contents

- [About](#about-the-project)
- [Setup](#setup)
- [Modeling](#modeling)

---
## About The Project
Following the udemy Machine Learning course of https://www.udemy.com/course/machinelearning

Learning to test and compare different Regression, Classification, Clustering, Deep learning and NLP models

Association and Reinforcement Learning

Model selection (Grid search and K Fold Cross) and XGBoost

---

## Setup
> **Install packages first**
```
pip install pandas-datareader
pip install numpy
pip install pandas
pip install -U scikit-learn
```

---

## Modeling
**1. Data Preprocessing and Exploratory Data Analysis**
  >- Check and Understand Data
  >- Convert datatypes
  >- Clean Data ( Remove anything unused, Duplicates) Removed rows with missing values 
  
**2. Train/Test Split**
  >- Split data to train and test set (20~25%)
  
**3. Prepare for Modeling**
  >- Feature Engineer - Aggregations ( Any Calculations)
  >- Transform Data ( Normalize, Standardize, One Hot Encoder...)
  >- Feature Selection ( Dimension?)
  
**4. Picking models**
  >- Try out Models such as Regression or Classification Models
  
**5. Model Selection**
  >- Grid Search, Cross-Validation (Kfold...)
  >- XGBoost
  
**6. Model Tuning and Picking Best Model**
  >- Hyperparameter tuning ( Using Cross-Validation, Grid Search, Bayesian Optimization...)
  >- Compare Accuracy and pick best model
