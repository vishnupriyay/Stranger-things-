# 🔮 Stranger Things Season 5 — AI Prediction Model

This project predicts **which characters are most likely to survive or die in Stranger Things Season 5** using machine learning techniques applied to past season character traits and story patterns.

The project was created for **fun + data science learning** and also featured in a YouTube video.

---

## 🧠 Model Pipeline Overview
The prediction pipeline includes:

✔ Exploratory Data Analysis using Seaborn  
✔ Categorical feature preprocessing using **OneHotEncoder**  
✔ Numerical feature normalization with **Min-Max Scaler**  
✔ Character grouping using **K-Means Clustering**  
✔ **Linear Regression** to estimate survival probability  
✔ Final ranking and prediction for each character

---

## 📌 Why These Algorithms?
| Technique | Purpose |
|----------|---------|
| Seaborn EDA | Understand correlations & patterns |
| OneHotEncoder | Convert categorical traits (e.g., role, faction) into numeric |
| MinMaxScaler | Scale all features to same range for fair clustering |
| K-Means | Group similar character archetypes |
| Linear Regression | Assign survival probability score |

---

## 📁 Project Structure
project/
│── StrangerThings_Prediction.ipynb
│── data.csv
│── README.md
