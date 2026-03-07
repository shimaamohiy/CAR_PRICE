# Car Price Prediction 🚗

A machine learning project that predicts car prices using a dataset of **14,912 vehicle records**. The project implements a complete data science workflow including data preprocessing, exploratory data analysis (EDA), feature engineering, and training multiple regression models.

---

# Project Overview

The goal of this project is to build predictive models capable of estimating car prices based on various vehicle attributes such as manufacturer, engine specifications, mileage, fuel type, and production year.

The project demonstrates a full **machine learning pipeline**, from raw data processing to model evaluation.

---

# Dataset

The dataset contains **14,912 rows** with multiple features describing cars, including:

* Manufacturer
* Model
* Production Year
* Engine Volume
* Cylinders
* Mileage
* Fuel Type
* Transmission
* Drive Wheels
* Price

---

# Data Preprocessing

Several preprocessing steps were applied to prepare the dataset for modeling:

* Handling missing values
* Cleaning mileage values
* Converting engine volume to numeric format
* Removing outliers
* Fixing inconsistent categorical values

---

# Feature Engineering

New features were created to improve model performance:

* **Car Age** = Current Year – Production Year
* Processed **engine volume**
* Cleaned **mileage values**

---

# Exploratory Data Analysis (EDA)

Visual analysis was performed to understand relationships between features and car prices.

# Machine Learning Models

Several regression models were trained and evaluated:

* Ridge Regression (with Polynomial Features)
* K-Nearest Neighbors (KNN)
* Random Forest Regressor
* XGBoost Regressor

---

# Model Evaluation

Models were evaluated using:

* **RMSE (Root Mean Squared Error)**
* **R² Score**

The comparison helped determine which algorithm provides the best predictions for car prices.

---

# Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Matplotlib
* Seaborn
* Jupyter Notebook

---

# Project Structure

```
CAR_PRICE_PREDICTOR
│
├── CAR_PRICE.ipynb
├── train_data.csv
├── test_data.csv
├── images
└── README.md
```

---

# Key Skills Demonstrated

* Data Cleaning & Preprocessing
* Feature Engineering
* Exploratory Data Analysis
* Machine Learning Model Training
* Model Evaluation & Comparison

---

