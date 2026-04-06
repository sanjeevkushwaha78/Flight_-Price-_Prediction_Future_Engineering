# ✈️ Flight Price Prediction - EDA & Feature Engineering

## 📌 Project Overview
This project focuses on cleaning and transforming flight data to prepare it for machine learning models that predict ticket prices.

---

## 🎯 Objectives
- Clean raw flight dataset
- Perform feature engineering
- Encode categorical variables
- Prepare dataset for prediction models

---

## 📂 Dataset
- Source: Excel file
- Features include:
  - Airline
  - Source & Destination
  - Date of Journey
  - Arrival & Departure Time
  - Duration
  - Total Stops

---

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

---

## 🧹 Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Converted data types

---

## ⚙️ Feature Engineering

### Date Features
- Extracted Day, Month, Year

### Time Features
- Arrival Hour & Minutes
- Departure Hour & Minutes

### Stops
- Converted categorical stops to numerical

---

## 🔢 Encoding
Used OneHotEncoder for:
- Airline
- Source
- Destination

---

## 📊 Final Dataset
- Fully numeric dataset
- Ready for machine learning models

---

## 🔍 Key Insights
- Stops and airline affect pricing significantly
- Time-based features are important
- Feature engineering improves model readiness

---

## 🚀 Future Work
- Apply regression models
- Hyperparameter tuning
- Model evaluation (RMSE, R²)
