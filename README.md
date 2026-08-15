# Oasis Infobyte Internship Projects
**Author: Prakhar Srivastava**

## 📌 Project Overview

This repository contains the projects completed as part of the **Oasis Infobyte Internship Program (OIBSIP)**.

The internship focuses on applying Python, Data Analysis, Data Visualization, and Machine Learning concepts to real-world datasets and problems.

---
# 📂 Internship Tasks

## ✅ Task 1: Iris Flower Classification

### 🎯 Objective

Build a machine learning classification model to predict the species of an Iris flower based on its physical measurements.

### 🌸 Classes

- Setosa
- Versicolor
- Virginica

### 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

### 📊 Exploratory Data Analysis

The following analyses were performed:

- Dataset shape and data types
- Null value checking
- Descriptive statistics
- Pairplot visualization
- Boxplot visualization
- Feature selection analysis

### 🤖 Machine Learning Models

- Logistic Regression
- Random Forest Classifier

### 📈 Evaluation Metrics

- Accuracy Score
- Confusion Matrix
- Precision
- Recall
- F1-Score

### 🏆 Result

Both Logistic Regression and Random Forest achieved **100% accuracy** on the test dataset.

Since both models performed equally well, **Random Forest** was selected as the final model because of its robustness and ability to handle complex decision boundaries.

---

## ✅ Task 2: Unemployment Analysis with Python

### 🎯 Objective

Perform Exploratory Data Analysis on unemployment data to identify regional and temporal trends, 
with a focus on the impact of the COVID-19 pandemic on unemployment rates in India.

### 🛠️ Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

### 📊 Analysis Performed

- Dataset loading and inspection
- Missing value analysis
- Data type conversion
- Region-wise average unemployment analysis
- Month-wise unemployment trends
- Time-series analysis
- State-wise unemployment comparison
- Correlation analysis
- Pre-COVID vs Post-COVID comparison

### 📈 Visualizations

- Time-series line chart
- Top 10 states by average unemployment rate
- Correlation heatmap
- Regional and monthly trend visualizations

### 📝 Key Focus

The analysis examines changes in unemployment rates before and after the COVID-19 period and highlights regional and temporal variations in unemployment across India.

---

## ✅ Task 3: Car Price Prediction with Machine Learning

### 🎯 Objective

Build a machine learning regression model to predict the selling price of a used car based on features such as brand,
car age, mileage, fuel type, seller type, and transmission.

### 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

### 📂 Dataset

The project uses the **Vehicle Dataset from CarDekho**, containing information about used cars and their selling prices.

### 🧹 Data Cleaning

The following preprocessing steps were performed:

- Checked for missing values
- Removed duplicate records
- Checked categorical values
- Standardized categorical variables
- Verified data types

### ⚙️ Feature Engineering

Two important features were created:

- **Car Age** – calculated from the manufacturing year
- **Brand** – extracted from the car name

### 📊 Exploratory Data Analysis

The following visualizations were created:

- Selling Price Distribution
- Selling Price vs Fuel Type Box Plot
- Selling Price vs Car Age Scatter Plot
- Feature Correlation Heatmap

### 🔄 Categorical Encoding

Categorical variables were converted into numerical features using **One-Hot Encoding**.

### 🤖 Machine Learning Models

Two regression models were trained:

- Linear Regression
- Random Forest Regressor

### 📈 Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

### 🏆 Model Comparison

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 1.809 | 3.399 | 0.552 |
| Random Forest | **1.409** | 3.429 | 0.544 |

### 🥇 Final Model

**Random Forest Regressor** was selected as the final model because it achieved the lowest **MAE (1.409)**, indicating a lower average prediction error.

Feature importance analysis was also performed to identify the features that contributed most to the model's predictions.

---

# 📁 Repository Structure

```text
OIBSIP/
│
├── README.md
│
├── Task1_Iris_Classification.ipynb
│
├── Task2_Unemployment_Analysis.ipynb
│
└── Task3_Car_Price_Prediction.ipynb
