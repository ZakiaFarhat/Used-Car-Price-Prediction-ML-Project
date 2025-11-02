# Used-Car-Price-Prediction-ML-Project

This project predicts the **selling price of used cars** in the Indian market using various machine learning models.  
---
## 📌 Project Overview

The goal of this project is to:
- Perform **Exploratory Data Analysis (EDA)**
- Identify key features affecting used car prices
- Build & compare multiple ML models
- Select the best-performing model
- Export the trained model for real-world use

---

## 🗂️ Dataset

| Column Name       | Description |
|-------------------|-------------|
| name              | Car name / model |
| year              | Manufacturing year |
| km_driven         | Total km driven |
| fuel              | Fuel type |
| seller_type       | Dealer / Individual |
| transmission      | Manual / Automatic |
| owner             | Ownership count |
| mileage           | Mileage (kmpl) |
| engine            | Engine CC |
| max_power         | Max power (bhp) |
| seats             | Number of seats |
| selling_price     | **Target variable** |

Dataset file included: `selected_data.csv`

---

## 🛠️ Machine Learning Models Used

| Model | RMSE ↓ | MAE ↓ | R² ↑ |
 Linear Regression 
 Decision Tree 
 Random Forest
 XGBoost 
👉 Final chosen model: **Random Forest Regressor**

---

##  Workflow Summary

1. Data Cleaning & Preprocessing  
2. Handling Missing Values  
3. Categorical Encoding (OneHotEncoder)  
4. Feature Scaling (StandardScaler)  
5. Train-Test Split  
6. Model Training & Hyperparameter Tuning  
7. Model Evaluation  
8. Saving the Best Model (`random_forest_model.pkl`)

---

```bash
pip install -r requirements.txt
