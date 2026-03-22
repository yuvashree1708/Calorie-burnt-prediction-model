# 🔥 Calories Burnt Predictor (Machine Learning)

## 📌 Overview
This project aims to predict the number of calories burned during physical activity using machine learning.  
The model uses biometric and exercise-related features such as age, gender, height, weight, duration, heart rate, and body temperature.

---

## 🎯 Objective
To build a regression model that can accurately estimate calorie expenditure based on physiological and activity data.

---

## 📂 Dataset
The dataset contains the following features:

- **User_ID** – Unique identifier for each individual  
- **Gender** – Male/Female  
- **Age** – Age of the individual  
- **Height** – Height in cm  
- **Weight** – Weight in kg  
- **Duration** – Duration of exercise (minutes)  
- **Heart_Rate** – Heart rate during exercise  
- **Body_Temp** – Body temperature  
- **Calories** – Target variable (calories burned)  

---

## ⚙️ Workflow

1. **Data Preprocessing**
   - Handling categorical variables (Gender encoding)
   - Removing unnecessary columns (User_ID)
   - Correlation analysis

2. **Feature Selection**
   - Removing highly correlated features

3. **Train-Test Split**
   - 90% training, 10% validation

4. **Feature Scaling**
   - Standardization using `StandardScaler`

5. **Model Training**
   - Linear Regression (baseline model)
   - Optional: Random Forest for improved performance

6. **Evaluation**
   - Metric used: **Mean Absolute Error (MAE)**

---

## 📊 Results

- **Mean Absolute Error (MAE): ~8.41**
  
This means the model predicts calorie expenditure with an average error of approximately **8 calories**, indicating good performance for this dataset.

---
