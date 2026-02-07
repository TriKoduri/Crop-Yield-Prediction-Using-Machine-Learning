# 🌾 Crop Yield Prediction Using Machine Learning

## 📌 Problem Statement
Accurate crop yield prediction is crucial for agricultural planning, food security, and economic stability. Traditional estimation methods often fail to account for complex relationships between climatic conditions, agricultural inputs, and crop types.  
This project aims to build a machine learning model that predicts crop yield using real-world agricultural data.

---

## 🎯 Objective
To develop a predictive model that estimates crop yield based on factors such as:
- Crop type
- Area cultivated
- Annual rainfall
- Fertilizer usage
- Pesticide usage
- Season and location

---

## 📊 Dataset
- **Source:** Public agricultural dataset  
- **Records:** ~19,500 rows  
- **Features:**  
  `Crop`, `Crop_Year`, `Season`, `State`, `Area`, `Production`,  
  `Annual_Rainfall`, `Fertilizer`, `Pesticide`
- **Target Variable:** `Yield`

---

## ⚙️ Model Pipeline
1. **Data Loading & Exploration**
   - Dataset inspection
   - Shape, data types, and missing value analysis

2. **Data Cleaning & Preprocessing**
   - Removal of duplicates
   - Filtering invalid values
   - Log transformation of yield to handle skewness
   - One-hot encoding for categorical variables
   - Train-test split

3. **Model Selection**
   - Baseline Model: Linear Regression
   - Final Model: Random Forest Regressor

4. **Model Training**
   - Model trained on log-transformed yield values

5. **Evaluation Metrics**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score

---

## 📈 Results & Performance
| Metric | Value |
|------|------|
| MAE | ~0.068 |
| RMSE | ~0.183 |
| R² Score | ~0.97 |

- High R² score indicates strong predictive performance.
- Log transformation significantly improved model stability.
- Feature importance analysis highlights crop type and production as major contributors.

---

## 📉 Visualizations
- Yield distribution (before & after log transformation)
- Feature importance plot
- Actual vs Predicted yield scatter plot

These visualizations validate the effectiveness and reliability of the model.

---

## 🧠 Inference & Insights
- Crop type plays a major role in yield prediction.
- Rainfall and agricultural inputs significantly influence output.
- The model generalizes well across different crops and regions.

---

## 🛠️ Technologies Used
- Python
- Pandas, NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

## 📂 Code & Notebook
- **Jupyter Notebook:** `Crop_Yield_Prediction_Using_Machine_Learning.ipynb`
- **Google Colab:**  
  👉 https://colab.research.google.com/drive/14nimkNMJJyMupgO8-b6O4rxd1QiDZ9gO?usp=sharing

---

## 🚀 Future Enhancements
- Incorporate soil quality and temperature data
- Time-series forecasting for yearly yield prediction
- Deploy the model using Flask or FastAPI

---

## 👩‍💻 Author
**Trisha Koduri**  
AI & Machine Learning Engineer Aspirant
