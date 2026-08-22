# 🏠 House Price Prediction: From Linear Regression to XGBoost

📖 **About**
This project demonstrates an end-to-end machine learning workflow for predicting house prices in Tehran. It covers everything from data preprocessing and feature engineering to model evaluation. 

Initially built using a basic **Linear Regression** model, the project has been upgraded to include powerful ensemble methods like **Random Forest** and **XGBoost**. Additionally, the entire workflow was restructured using **Scikit-learn Pipelines** to ensure clean, maintainable, and leak-proof code.

🚀 **Technologies**
* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Pipelines, ColumnTransformer)
* XGBoost

📂 **Dataset**
The dataset used in this project contains information about residential properties in Tehran. It is included directly in this repository, so you can download it and follow the notebook step by step without any additional setup.

📊 **Project Workflow**
1. Data Cleaning & Handling Missing Values
2. Exploratory Data Analysis (EDA)
3. Feature Engineering & One-Hot Encoding
4. Baseline Model: Linear Regression
5. **Advanced Models:** Random Forest & XGBoost
6. Pipeline Implementation for all models
7. Model Evaluation & Comparison
8. Feature Importance Extraction

📊 Model Performance Comparison

| Model | MAE (USD) | RMSE (USD) | R² Score |
|:---|:---:|:---:|:---:|
| **Linear Regression** | 75,984.62 | 164,713.54 | 0.6134 |
| **Random Forest** | **56,964.69** | **152,961.30** | **0.6666** |
| **XGBoost** | 58,623.35 | 156,692.60 | 0.6502 |

> **Note:** The Random Forest model achieved the best overall performance, significantly reducing the prediction error and explaining roughly 66.6% of the variance in house prices.

📈 **Results & Visualizations**
Here are some key visual insights and evaluation metrics from the project:

**1. Actual vs. Predicted Prices (Linear Regression Baseline)**

<img width="691" height="546" alt="image" src="https://github.com/user-attachments/assets/063c2fd8-f454-4389-b6ab-3c55502605ac" />

**2. Model Performance Comparison (R² Score )**

<img width="691" height="450" alt="image" src="https://github.com/user-attachments/assets/84de4146-6bdf-4a02-9667-8b869ea91af2" />

**3. What Drives House Prices? (Feature Importance)**

<img width="946" height="546" alt="image" src="https://github.com/user-attachments/assets/7559a65e-4626-4d86-852d-273dd33394d0" />

---
👨‍💻 **Author**

**Mehdi Ferdosi**  
Computer Science Student | Machine Learning Enthusiast  
GitHub: [https://github.com/mehdifr24](https://github.com/mehdifr24)
