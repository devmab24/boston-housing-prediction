# 🏡 House Price Prediction (Linear & Ridge Regression)

This project explores **house price prediction** using machine learning.
I worked with the **Boston Housing dataset** to understand how different features (like rooms, age, taxes, etc.) influence house prices, and compared **Linear Regression** with **Ridge Regression**.

---

## 📌 Project Overview

* **Goal**: Predict median house prices based on housing features.
* **Dataset**: Boston Housing dataset (sklearn).
* **Models used**:

  * Linear Regression
  * Ridge Regression

---

## 🔍 Key Steps

1. **Data Exploration**

   * Checked distributions, missing values, and feature relationships.
   * Examined multicollinearity among features.

2. **Model Training**

   * Trained both Linear Regression and Ridge Regression.
   * Evaluated models using R², RMSE, and MAE.

3. **Insights**

   * Identified the **top 5 most influential features** from Ridge Regression:

   | Rank | Feature | Coefficient |
   | ---- | ------- | ----------- |
   | 1    | B       | -3.52       |
   | 2    | NOX     | 3.35        |
   | 3    | LSTAT   | 3.02        |
   | 4    | AGE     | -3.01       |
   | 5    | TAX     | -1.81       |

   * Ridge Regression handled multicollinearity better and provided more reliable feature importance than plain Linear Regression.

---

## 📊 Results

* **Linear Regression** performed well but was sensitive to multicollinearity.
* **Ridge Regression** improved stability and gave clearer insights on influential features.

---

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/house-price-prediction.git
   cd house-price-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:

   ```bash
   jupyter notebook house_price_pred_model.ipynb
   ```

---

## 💡 Reflections

This project helped me practice:

* Comparing regression models (Linear vs Ridge).
* Handling multicollinearity in features.
* Interpreting model coefficients to extract real-world insights.

I learned that **model interpretability is as important as accuracy**—knowing which features matter most helps turn numbers into business value.

---

## 📬 Connect

If you find this project interesting or want to collaborate:

* 🌐 [LinkedIn](https://www.linkedin.com/in/devmab/)
* 🐙 [GitHub](https://github.com/devmab24/)

Do you want me to also **write the requirements.txt** for you (listing sklearn, pandas, matplotlib, etc.) so the repo is fully reproducible?
