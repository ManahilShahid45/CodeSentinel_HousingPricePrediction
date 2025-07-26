# 🏠 Housing Price Prediction with Linear Regression

A hands-on machine learning project to predict housing prices using linear regression. This project walks through the full ML pipeline using the Boston or California housing dataset, covering data preparation, model training, and evaluation.

---

## 🎯 Objective

The goal is to build a predictive model that estimates housing prices based on multiple features. This task is designed to help understand the basics of:

- Supervised Learning (Regression)
- Machine Learning pipeline
- Model evaluation using error metrics

---

## 📊 Dataset Used

- **Boston Housing** or **California Housing** dataset (from `sklearn.datasets`)
- Features include:
  - Median income
  - Number of rooms
  - Crime rate
  - Property tax rate
  - And more...

---

## 🧰 Tools & Libraries

- `pandas` – Data manipulation
- `numpy` – Numerical operations
- `scikit-learn` – ML modeling and evaluation

---

## 🧪 Steps Involved

1. **Data Loading**
   - Load dataset via `sklearn.datasets` or CSV
2. **Exploratory Analysis**
   - Understand feature correlations
   - Detect missing values
3. **Data Splitting**
   - Train-test split using `train_test_split()`
4. **Model Training**
   - Fit a `LinearRegression` model
5. **Evaluation**
   - Predict on test set
   - Evaluate using:
     - Root Mean Squared Error (RMSE)
     - R² Score

---

## 📈 Sample Results

| Metric | Value |
|--------|-------|
| RMSE   | 4.7   |
| R²     | 0.57  |

_(Note: Results vary depending on dataset and preprocessing)_

---

## 💡 Skills Gained

- 📊 Exploratory Data Analysis (EDA) using `pandas` and `numpy`
- 🧹 Data cleaning, feature selection, and scaling
- 🧠 Training and evaluating Linear Regression models with `scikit-learn`
- 🧪 Model validation using RMSE and R²
- ⚙️ Understanding and building a basic ML pipeline
- 📁 Experience working with real-world housing datasets
- 💻 Writing modular, reproducible Python code

---

## ▶️ How to Run

```bash
pip install -r requirements.txt
python CodeSentinel_Task04.py
