Sure! Here's a **rewritten and refreshed version** of your content — more concise, modern tone, yet still professional and detailed:

---

# 🤖 AI/ML Internship Portfolio – DevelopersHub

This repository showcases the tasks completed during my **AI/ML Engineering Internship** at **DevelopersHub Corporation**. The projects span key machine learning domains such as **data exploration**, **predictive modeling**, and **real-world stock forecasting** using industry-standard datasets.

---

## 🗂️ Project Summary

| Task | Title                         | Algorithm               | Category       | Output Description                  |
| ---- | ----------------------------- | ----------------------- | -------------- | ----------------------------------- |
| 1    | Iris Dataset EDA              | None (EDA only)         | Data Analysis  | Visual insights into feature trends |
| 2    | Heart Disease Classifier      | Logistic Regression     | Classification | Predicts disease presence (Yes/No)  |
| 3    | Apple Stock Price Forecasting | Random Forest Regressor | Regression     | Predicts next-day closing price     |

---

## 🌼 Task 1: Iris Dataset — Exploratory Data Analysis

### 🎯 Goal:

Uncover patterns in the **Iris dataset** through visualizations and statistical analysis.

### 📊 Data Info:

* **Source:** `seaborn` built-in dataset
* **Features:** sepal/petal length & width, species

### 🛠️ Tools Used:

* `pandas`, `seaborn`, `matplotlib`

### 🔍 Deliverables:

* Scatter plots by species
* Histograms & box plots
* Outlier detection

### 🧠 Key Insights:

* No missing data
* Clear cluster for *setosa*
* Moderate feature overlap in *versicolor* & *virginica*

---

## ❤️ Task 2: Heart Disease Prediction

### 🎯 Goal:

Build a classification model to predict **heart disease risk** using patient health metrics.

### 📊 Data Info:

* **Dataset:** `heart.csv` (UCI Heart Disease)
* **Features:** age, cholesterol, heart rate, slope, etc.

### 🛠️ Tools Used:

* `pandas`, `numpy`, `seaborn`, `matplotlib`
* `scikit-learn`, `joblib`

### 🤖 Model:

* **Logistic Regression**

### 📈 Metrics:

* Accuracy, Confusion Matrix, ROC-AUC, Classification Report

### 📊 Visuals:

* ROC Curve, Confusion Matrix, Feature Importance

### 💾 Artifacts:

* `heart_disease_model.pkl`
* `scaler.pkl`

---

## 📈 Task 3: Apple Stock Price Prediction

### 🎯 Goal:

Forecast the **next day’s closing price** of Apple stock (AAPL) using historical trends and technical indicators.

### 📊 Data Info:

* **Source:** `yfinance` API (Jan 2022 – Dec 2024)
* **Features:** OHLC, Volume, Moving Averages, Volatility, etc.

### 🛠️ Tools Used:

* `yfinance`, `pandas`, `numpy`, `seaborn`, `matplotlib`, `plotly`
* `scikit-learn`, `joblib`

### 🤖 Model:

* **Random Forest Regressor**

### 📈 Metrics:

* Mean Squared Error (MSE), R² Score

### 📊 Visuals:

* Candlestick charts
* Feature correlation heatmaps
* Actual vs Predicted price plots

### 💾 Artifacts:

* `aapl_rf_model.pkl`
* `aapl_scaler.pkl`

---

## ⚙️ How to Run the Projects

```bash
# 1. Clone this repository
git clone https://github.com/your-username/AI-ML-Internship-Tasks.git
cd AI-ML-Internship-Tasks

# 2. Go into a specific task
cd task_2_heart_disease_prediction

# 3. Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn yfinance plotly joblib

# 4. Run the Jupyter notebook
jupyter notebook heart_disease_analysis.ipynb
```

---

## 🙋‍♂️ Author

**Muhammad Talha**
AI/ML Intern – DevelopersHub Corporation
GitHub: [@Muhammad Talha)(https://github.com/Muhammad-Talha-000)
