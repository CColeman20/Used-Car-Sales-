# Used-Car-Sales-
🚗 Used Car Sales Price Prediction
This project analyzes used car listings to predict their market prices using machine learning models. The goal is to help dealerships and individual sellers better estimate a car's value based on its features and specifications.

📊 Objective
Build a regression model to accurately predict used car prices based on attributes such as:

Vehicle type

Engine size

Mileage

Registration year

Gearbox type

Fuel type

Brand

🧠 Tools & Technologies
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

Jupyter Notebook

🛠️ Process Overview
1. Data Preprocessing
Handled missing values and duplicates

Encoded categorical variables (e.g., gearbox, brand)

Converted dates and numerical features into consistent formats

2. Exploratory Data Analysis (EDA)
Visualized distribution of car prices, mileage, and registration years

Identified trends and outliers affecting price

3. Feature Engineering
Created new features such as "car age"

Removed low-variance and irrelevant columns

4. Model Development
Trained multiple regression models:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Evaluated using RMSE and R²

5. Results
The Random Forest model performed best with the lowest RMSE and highest R² score, providing accurate and robust predictions.

📈 Key Insights
Newer vehicles with low mileage retain higher value

Gearbox and brand have strong influence on resale price

Data cleaning and proper feature selection significantly improved model performance
