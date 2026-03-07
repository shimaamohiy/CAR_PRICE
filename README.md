# CAR_PRICE
This project focuses on predicting car prices using machine learning techniques based on a dataset containing approximately 14,912 records of car specifications.

The project includes a full data science pipeline starting from data preprocessing and cleaning, followed by feature engineering, exploratory data analysis, and training multiple regression models to predict car prices.

Key steps in the project include:

* Data Cleaning: Handling missing values, fixing encoding issues, filtering invalid fuel types, and removing outliers.
* Feature Engineering: Creating new features such as car age and processing numerical attributes like mileage, engine volume, and cylinders.
* Data Transformation: Applying one-hot encoding for categorical variables and label encoding for manufacturer and model features.
* Data Scaling: Standardizing numerical features using StandardScaler.
* Exploratory Data Analysis: Visualizing relationships between features and price using scatter plots and box plots.

Multiple machine learning models were implemented and evaluated, including:

* Ridge Regression with Polynomial Features
* K-Nearest Neighbors (KNN)
* Random Forest Regressor
* XGBoost Regressor

Model performance was evaluated using RMSE and R² metrics, and comparisons were conducted to determine the most effective model for predicting car prices.

This project demonstrates practical skills in data preprocessing, feature engineering, machine learning model development, and performance evaluation using Python libraries such as Pandas, NumPy, Scikit-learn, XGBoost, Seaborn, and Matplotlib.
