# 🏡 House Price Prediction using Machine Learning

## 📌 Overview

This project focuses on predicting house prices using machine learning techniques. The model is trained on the **California Housing Dataset** and uses the powerful **XGBoost Regressor** to achieve accurate predictions.


The workflow includes:

* Data loading and preprocessing
* Exploratory Data Analysis (EDA)
* Feature correlation analysis
* Model training using XGBoost
* Model evaluation using performance metrics

---

## 🚀 Features

* 📊 Data visualization with **Matplotlib** and **Seaborn**
* 🔍 Correlation heatmap for feature analysis
* 🤖 Machine Learning model using **XGBoost**
* 📈 Performance evaluation using:
  * R² Score
  * Mean Absolute Error (MAE)
* 📉 Visualization of Actual vs Predicted prices

---

## 🗂️ Dataset

* **Dataset Used:** California Housing Dataset
* Source: `sklearn.datasets.fetch_california_housing()`

### Features:

* MedInc → Median income
* HouseAge → Median house age
* AveRooms → Average number of rooms
* AveBedrms → Average number of bedrooms
* Population → Block population
* AveOccup → Average house occupancy
* Latitude → Latitude location
* Longitude → Longitude location
* 🎯 Target Variable: **House Price**

---

## ⚙️ Tech Stack

* Python 
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* XGBoost

---

## 📊 Project Workflow

### 1. Data Loading

* Load dataset from sklearn
* Convert to Pandas DataFrame

### 2. Data Preprocessing

* Check for missing values
* Analyze statistical summary

### 3. Exploratory Data Analysis

* Correlation matrix
* Heatmap visualization

### 4. Train-Test Split

* 80% Training data
* 20% Testing data

### 5. Model Training

* Algorithm: **XGBoost Regressor**
* Fit model on training data

### 6. Model Evaluation

* R² Score
* Mean Absolute Error (MAE)

### 7. Visualization

* Scatter plot:

  * Actual Prices vs Predicted Prices

---

## 📈 Results

* The model performs well on both training and test datasets.
* Visualization shows strong alignment between actual and predicted prices.



