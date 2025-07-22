# 📊 Diabetes Progression Prediction using Linear Regression

This project demonstrates a hands-on implementation of **Linear Regression** using the **Diabetes dataset** from `sklearn.datasets`.  
The aim is to predict the progression of diabetes in patients one year after baseline, based on health-related features.

---

## ❓ Why This Dataset?

Initially, I tried implementing linear regression on the `load_boston()` dataset, but it has been removed from recent versions of scikit-learn due to ethical concerns.  
Even after downgrading, issues persisted due to version mismatches with other libraries.  
So, I used the **Diabetes dataset** — a clean, similar, and built-in option that supports regression modeling.

---

## 📁 Dataset Overview

- 📌 **Samples:** 442 patients  
- 📌 **Features (10 total):**
  - Age  
  - Sex  
  - Body Mass Index (BMI)  
  - Average Blood Pressure  
  - Six blood serum measurements  
- 🎯 **Target:** A quantitative measure of disease progression after one year

---

## 🔧 What This Project Covers

✔️ Loading dataset from `sklearn.datasets`  
✔️ Converting data into a Pandas DataFrame  
✔️ Separation of input features (X) and output label (y)  
✔️ Train-Test Split using `train_test_split`  
✔️ Standardizing using `StandardScaler`  
✔️ Fitting Linear Regression using `LinearRegression`  
✔️ Cross-validation using `cross_val_score`  
✔️ Predicting and comparing results  
✔️ Plotting important features  
✔️ Scoring with R², MSE, etc.

---

## 📦 Requirements

Install all required libraries with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

---

## 📩 Contact & Contribution

For contributions, feedback, or collaborations, feel free to reach out:  
- **Author:** Shreya Gupta
- **Email:** shreyagupta119809@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/shreya-gupta-2a6a292ab

---

## 🔖 Tags  
#DataScience #Python #TVShows #APIDatasets #MachineLearning #OpenData #DataVisualization  

