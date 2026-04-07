# 🌍 End-to-End AQI Prediction Pipeline

## 📌 About the Project

In this project, I worked with real-world air pollution data to understand how different pollutants affect Air Quality Index (AQI) and to build models that can predict it.

The idea was not just to train a model, but to explore the data, compare approaches, and understand what actually works for this kind of problem.

---

## 📊 What I Did

* Cleaned and handled missing data
* Explored trends and relationships between pollutants and AQI
* Built multiple models:

  * Linear Regression
  * Random Forest
  * Neural Network
* Evaluated performance using MAE, RMSE, and R²

---

## 📈 Results

| Model             | MAE       | RMSE      | R²       |
| ----------------- | --------- | --------- | -------- |
| Linear Regression | 24.86     | 40.84     | 0.81     |
| Random Forest     | **19.34** | **31.86** | **0.88** |
| Neural Network    | 24.76     | 38.36     | 0.83     |

👉 Random Forest performed the best overall.

---

## 🔍 Key Takeaways

* PM2.5 and PM10 have a strong impact on AQI
* Random Forest handled the data better than other models
* Neural networks didn’t add much value for this tabular dataset

---

## ⚠️ Limitations

* Missing values were filled using median (may introduce bias)
* No weather data included
* Model doesn’t capture long-term time patterns

---

## 🚀 What I’d Improve Next

* Add weather-related features
* Try XGBoost for better performance
* Turn this into a simple web app

---

## 🛠️ Tools Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow

---


Nesa Sankaran
