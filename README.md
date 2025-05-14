# 📊 Salary Prediction using Multiple Linear Regression

This project demonstrates a simple yet effective approach to predicting salaries based on **Years of Experience** and **Age** using **Multiple Linear Regression** in Python. It includes data preprocessing, visualization, training, testing, and evaluation.

---

## 📁 Dataset

The dataset contains 30 observations and 3 columns:

* `YearsExperience`: Number of years of professional experience
* `Age`: Age of the employee
* `Salary`: Annual salary in USD

**Sample Preview:**

| YearsExperience | Age  | Salary |
| --------------- | ---- | ------ |
| 1.1             | 21.0 | 39343  |
| 1.3             | 21.5 | 46205  |
| 1.5             | 21.7 | 37731  |

---

## 🔍 Exploratory Data Analysis

* ✅ No missing values found
* 📊 Pairplot reveals a linear relationship between features and target
* 🔥 Heatmap shows a high correlation among variables

---

## 📦 Libraries Used

```python
pandas
seaborn
matplotlib
scikit-learn
```

---

## 🧪 Train-Test Split

* `80%` training data
* `20%` testing data
* Performed using `train_test_split` from `sklearn`

---

## 🤖 Model: Multiple Linear Regression

The model was trained using `LinearRegression` from `sklearn`.

**Model Accuracy**: `88.52%` on test data

**Regression Equation:**

```
Salary = (4882.15 * YearsExperience) + (2567.52 * Age) - 20612.69
```

---

## 📈 Predictions (Sample)

```python
Predicted Salaries for test data:
[118686.60, 67497.80, 101581.52, 74585.69, 54833.37, 58044.70]
```

---

## 📌 Key Takeaways

* Salary increases with both experience and age
* Multiple Linear Regression works well with this small, clean dataset
* This project demonstrates the full ML workflow: EDA → Modeling → Evaluation

---

## ▶️ Run it Yourself

To run the project:

1. Clone the repo or copy the notebook.
2. Ensure the dataset (`Salary_Data.csv`) is in the correct path.
3. Install required libraries using pip if not already installed:

```bash
pip install pandas seaborn matplotlib scikit-learn
```

4. Run the Jupyter Notebook or Python script.

---
