# 🛒 Customer Next Purchase Prediction System

## 🤖 Predicting Customer Next Purchase Using Machine Learning

**Analyze • Predict • Recommend • Deploy**

[![Python](https://img.shields.io/badge/🐍%20Python-3.x-blue?style=flat-square)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Multi--Class%20Classification-orange?style=flat-square)](https://scikit-learn.org/)
[![XGBoost](https://img.shields.io/badge/XGBoost-Classification-green?style=flat-square)](https://xgboost.readthedocs.io/)
[![Scikit-Learn](https://img.shields.io/badge/🧠%20Scikit--Learn-ML-orange?style=flat-square)](https://scikit-learn.org/)
[![Streamlit](https://img.shields.io/badge/🚀%20Streamlit-Deployment-red?style=flat-square)](https://streamlit.io/)

---

## 📌 Overview

The **Customer Next Purchase Prediction System** is a Machine Learning project designed to predict the **category a customer is most likely to purchase next** based on their historical purchasing behavior.

The project uses customer transaction data, feature engineering, classification models, and an interactive **Streamlit application** to generate predictions and personalized product recommendations.

### 🎯 Main Goal

> **Predict what a customer is likely to purchase next and recommend relevant products.**

This can support:

* 🛒 Personalized product recommendations
* 🎯 Targeted customer engagement
* 📈 Sales opportunities
* 📊 Data-driven marketing decisions

---

# 🔄 Project Workflow

```text
📊 Customer Data
      │
      ▼
🧹 Data Preparation
      │
      ▼
🔍 Exploratory Data Analysis
      │
      ▼
⚙️ Feature Engineering
      │
      ▼
🎯 Target Creation
      │
      ▼
🧠 ML Models
      │
      ▼
📊 Model Evaluation
      │
      ▼
🎯 Next Purchase Prediction
      │
      ▼
🛒 Product Recommendation
      │
      ▼
🌐 Streamlit Application
```

---

# ⚙️ Feature Engineering

The model uses customer purchasing behavior to create features such as:

* 🧾 Total orders
* 💰 Total spending
* 🛍️ Average order value
* 📦 Average quantity
* 🏷️ Average discount
* 🚚 Average delivery days
* 🛒 Unique products
* 🗂️ Unique categories
* ↩️ Return rate
* ⏱️ Days since last purchase

These customer-level features are generated from historical transactions.

---

# 🧠 Machine Learning

The project compares multiple classification models:

* Logistic Regression
* Random Forest
* XGBoost

The Streamlit application uses **XGBoost** for the next-purchase prediction workflow.

---

# 🎯 Prediction

The system generates the **Top-5 most probable purchase categories** with their probability scores.

```text
👤 Customer
     ↓
📊 Purchase Behavior
     ↓
🤖 XGBoost
     ↓
🏆 Top-5 Predictions
     ↓
🛒 Product Recommendations
```

The application displays the most likely category, prediction probability, Top-5 predictions, and a probability chart.

---

# 🛒 Personalized Product Recommendations

After predicting the most likely category, the system recommends products from that category based on **product rating and price**.

Each recommendation displays:

* Product name
* Brand
* Sub-category
* Price
* ⭐ Product rating

---

# 🌐 Streamlit Application

The project includes an interactive **Customer Next Purchase AI** application.

### 🚀 Features

* 👤 Customer selection
* 📊 Customer overview
* 🧾 Purchase history
* 🎯 Next purchase prediction
* 🏆 Top-5 predictions
* 📈 Probability visualization
* 🛒 Personalized recommendations
* 🔍 Customer behavior analysis

The application allows users to select a customer and generate an AI-powered prediction.

---

# 🛠️ Technologies Used

| Technology          | Purpose              |
| ------------------- | -------------------- |
| 🐍 Python           | Programming          |
| 📊 Pandas           | Data Analysis        |
| 🔢 NumPy            | Numerical Operations |
| 📈 Matplotlib       | Visualization        |
| 🎨 Seaborn          | Visualization        |
| 🧠 Scikit-Learn     | Machine Learning     |
| 🚀 XGBoost          | Classification       |
| 📓 Jupyter Notebook | Development          |
| 💾 Joblib           | Model Storage        |
| 🌐 Streamlit        | Deployment           |

---

# 📂 Project Contents

```text
02-Customer-Next-Purchase-Prediction/
│
├── 📄 README.md
├── 📓 customer_next_purchase_prediction.ipynb
├── 📓 deployment.ipynb
├── 🐍 app.py
├── 📊 customer_next_purchase_dataset.xlsx
├── 🤖 next_purchase_model.pkl
└── 🔤 label_encoder.pkl
```

---

# 💡 Real-World Use Case

```text
Customer Purchase History
          ↓
   Machine Learning
          ↓
 Next Purchase Prediction
          ↓
Personalized Recommendation
          ↓
 Better Customer Engagement
```

---

# 🧪 Project Status

### 🟢 Completed

* ✅ Data preparation
* ✅ EDA
* ✅ Feature engineering
* ✅ Target creation
* ✅ ML model development
* ✅ Model evaluation
* ✅ Top-K prediction
* ✅ Personalized recommendations
* ✅ Streamlit application

---

# 🚀 Future Improvements

* 🔹 Advanced recommendation systems
* 🔹 Sequential purchase modeling
* 🔹 Hyperparameter optimization
* 🔹 Real-time customer data
* 🔹 Automated model retraining
* 🔹 Cloud deployment

---

## 🚀 From Customer Data to Recommendations

### **Analyze → Learn → Predict → Recommend → Deploy**

---

### ⭐ Thank you for exploring this project!
