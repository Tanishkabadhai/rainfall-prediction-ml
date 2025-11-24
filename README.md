# 🌧️ Rainfall Prediction using Machine Learning

This project predicts rainfall using multiple weather-based features with a **Linear Regression** model.  
It includes model evaluation and visualizations of prediction results.

---

## 📁 Dataset Information

Features included in the dataset:

- day
- pressure
- maxtemp
- temparature
- mintemp
- dewpoint
- humidity
- cloud
- sunshine
- winddirection
- windspeed

Target variable:

- rainfall (1 = Rain, 0 = No Rain)

---

## 🧠 Model Used

- Algorithm: Linear Regression
- Train-Test Split: **80% – 20%**

📌 *Although rainfall is a binary variable, regression is used for learning and evaluation in this version.*

---

## 📊 Performance Results

| Metric | Score |
|--------|------|
| R² Score | **0.2406** |
| Mean Squared Error | **0.1627** |

> The model shows basic predictive capability.  
> Performance can be improved using advanced models like Logistic Regression or Random Forest.

---
## 📌 Dataset Source
Dataset downloaded from Kaggle:
https://www.kaggle.com/datasets/subho117/rainfall-prediction-using-machine-learning
Dataset belongs to the original author as per Kaggle licensing.
Used here for educational and research purposes only.


## ⚙️ How to Run

Install dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib


