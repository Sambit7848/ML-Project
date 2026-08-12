# 🤖 ML Project — Smart ATM Cash Refill Prediction

> **Predicting when an ATM may need a cash refill using Machine Learning.**

## 🎯 Project Overview

This project uses historical ATM data to predict **`Needs_Refill`** and support smarter cash refill planning.

### 🔄 ML Workflow

**Data → EDA → Preprocessing → Model Training → Evaluation → Tuning → Prediction**

## 🧠 Models Used

| Model                  |   Accuracy |
| ---------------------- | ---------: |
| 🥇 Gradient Boosting   | **96.45%** |
| 🌲 Random Forest       | **94.15%** |
| 🌳 Decision Tree       | **92.95%** |
| 📊 Logistic Regression | **87.95%** |

## 🔍 Key Analysis

* 📈 Exploratory Data Analysis
* 🧹 Data preprocessing & encoding
* 🤖 Classification modeling
* 🎯 Feature importance
* ⚙️ Hyperparameter tuning with **GridSearchCV**
* 💾 Model saving/loading with **Joblib**

## ⭐ Key Feature

The Random Forest analysis identified **Current_Cash_Balance** as the most important feature in the model.

## 🛠️ Tech Stack

`Python` • `Pandas` • `NumPy` • `Matplotlib` • `Seaborn` • `Scikit-learn` • `Joblib`

## 📂 Project Files

```text
ML Project/
│
├── Smart ATM Cash Refill Prediction System.ipynb
├── Smart_ATM_Cash_Refill_Prediction_System.pdf
└── README.md
```

## 🚀 Future Scope

Real-time ATM data • Time-series forecasting • API deployment • Dashboard integration • Cloud deployment

---

### 💡 Project Goal

**Reduce the risk of ATM cash-outs and support data-driven refill decisions.**
