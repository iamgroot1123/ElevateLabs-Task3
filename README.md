# Task 3: Linear Regression

This repository contains the third task of my internship at **Elevate Labs**, focused on understanding and implementing simple and multiple linear regression models.

## 📌 Objective

Build and evaluate predictive models using linear regression techniques:

- Simple Linear Regression
- Multiple Linear Regression

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 🔍 Steps Performed

1. **Data Loading & Preprocessing**  
   - Loaded the Housing dataset.
   - Converted categorical columns to numerical (Label Encoding).
   - Selected appropriate features for modeling.

2. **Train-Test Split**  
   - Split dataset into 80% training and 20% testing sets.

3. **Simple Linear Regression**  
   - Trained model using only `area` as predictor.
   - Evaluated using:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score

4. **Multiple Linear Regression**  
   - Trained model using multiple predictors (area, bedrooms, bathrooms, etc.).
   - Evaluated using same metrics.

5. **Result Analysis**  
   - Compared model performances.
   - Interpreted coefficients and insights from models.

6. **Visualization**  
   - Plotted regression line (for simple regression) to observe fit.

## 📁 Files

- `task3.ipynb` - Notebook containing all model training and evaluation code
- `Housing.csv` - Dataset used for regression tasks
- `README.md` - This documentation

## 📊 Dataset

Dataset: [Housing Price Prediction Dataset](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
