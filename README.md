#  Solar Power Prediction using Time-Series Machine Learning

## Overview
This project focuses on predicting solar AC power output using weather data, primarily irradiation.  
Unlike standard regression approaches, this model incorporates **time-series feature engineering** to capture temporal dependencies and realistic solar plant behavior.

---

##  Key Features
- Implemented **lag features** to capture past power generation trends  
- Used **rolling mean (moving averages)** to model short-term and long-term temporal patterns  
- Ensured **no data leakage** using chronological train-test split  
- Modeled **temporal continuity and system inertia** in solar power generation  
- Compared performance of **Linear Regression and Random Forest models**  

---

##  Results
- Achieved high prediction accuracy:
  - **Random Forest R² ≈ 0.99**
  - **Linear Regression R² ≈ 0.99**
- Demonstrated importance of time-series features in handling fluctuations due to environmental changes

---

##  Key Concepts Used
- Time-Series Feature Engineering  
- Lag Features  
- Rolling Mean (Moving Average)  
- Train-Test Split (Time-based)  
- Regression Models  

---

##  Tech Stack
- Python  
- Pandas  
- NumPy  
- Scikit-learn  

---

---

##  Insights
- Solar power output is highly dependent on irradiation but also influenced by **temporal patterns**
- Lag features help capture **recent trends and inertia**
- Rolling statistics help smooth fluctuations and improve robustness

---

##  Future Improvements
- Incorporate real-time weather forecast data  
- Deploy model using a web interface  
- Experiment with deep learning models (LSTM/GRU)

---

##  Author
Sujal Shankar  
Mechanical Engineering Student | Machine Learning Enthusiast
