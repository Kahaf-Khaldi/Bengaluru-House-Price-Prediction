# 🏠 Bengaluru House Price Prediction

This project focuses on predicting house prices in Bengaluru using machine learning techniques.  
It involves data cleaning, feature engineering, exploratory data analysis, and building a regression model to estimate property prices based on various features.

---

## Project Overview

The real estate market in Bengaluru is highly dynamic. This project aims to build a predictive model that can estimate house prices based on parameters such as location, size (BHK), total square feet, and number of bathrooms.

The dataset is preprocessed to handle missing values, remove outliers, and transform categorical variables before training the model.

---

##  Dataset

- **Source:** Bengaluru House Price Dataset  
- **Format:** CSV  
- **Target Variable:** `price`

### Key Features Used
- `location`
- `total_sqft`
- `bhk`
- `bath`
- `price`

---

## Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Data Preprocessing Steps

1. Removed unnecessary columns (`area_type`, `society`, `balcony`, `availability`)
2. Handled missing values
3. Converted `size` column into `BHK`
4. Transformed `total_sqft` into numerical format
5. Removed outliers based on price per square foot
6. One-hot encoded categorical features (`location`)
7. Scaled and prepared data for modeling

---

## Exploratory Data Analysis (EDA)

- Distribution of house prices
- Price per square foot analysis
- Relationship between BHK, bathrooms, and price
- Location-based price variation

---

## Model Building

- **Algorithm Used:** Linear Regression
- **Train-Test Split:** 80% training, 20% testing
- **Evaluation Metrics:**
  - R² Score
  - Model accuracy on test data

---

## Results

The model demonstrates reasonable accuracy in predicting house prices based on the selected features and performs well after removing outliers and applying proper feature engineering.

---
