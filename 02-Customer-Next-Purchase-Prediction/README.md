# 🛒 Customer Next Purchase Prediction System

## 🤖 Predicting Customer Next Purchase Using Machine Learning

**Analyze • Predict • Recommend • Deploy**

---

## 📌 Overview

The **Customer Next Purchase Prediction System** is a Machine Learning project that predicts the **category a customer is most likely to purchase next** based on their historical purchasing behavior.

The project uses customer transaction data, feature engineering, classification models, and an interactive **Streamlit application** to generate predictions and personalized product recommendations.

### 🎯 Main Goal

> **Predict what a customer is likely to purchase next and recommend relevant products.**

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

Customer purchasing behavior is converted into meaningful Machine Learning features such as:

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

These features are generated from each customer's historical transactions.

---

# 🧠 Machine Learning Models

The project compares multiple classification algorithms:

| Model               | Purpose                   |
| ------------------- | ------------------------- |
| Logistic Regression | Baseline classification   |
| Random Forest       | Ensemble classification   |
| XGBoost             | Final prediction workflow |

The application uses **XGBoost** for generating the next-purchase category predictions.

---

# 🎯 Prediction

Instead of providing only one possible category, the system generates **Top-5 next purchase predictions** with probability scores.

```text
👤 Customer
     ↓
📊 Purchase Behavior
     ↓
🤖 XGBoost
     ↓
🏆 Top-5 Categories
     ↓
🛒 Product Recommendations
```

The Streamlit application displays the most likely category, Top-5 predictions, probabilities, and a prediction chart.

---

# 🛒 Personalized Recommendations

After predicting the most likely purchase category, the system recommends products from that category based on **product rating and price**.

The application displays:

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
* 🔍 Customer behavior used by the model

The application allows users to select a customer and generate an AI-powered prediction.

---

# 🛠️ Technologies Used

| Technology              | Purpose              |
| ----------------------- | -------------------- |
| 🐍 Python               | Programming          |
| 📊 Pandas               | Data Analysis        |
| 🔢 NumPy                | Numerical Operations |
| 📈 Matplotlib & Seaborn | Visualization        |
| 🧠 Scikit-Learn         | Machine Learning     |
| 🚀 XGBoost              | Classification       |
| 📓 Jupyter Notebook     | Development          |
| 💾 Joblib               | Model Storage        |
| 🌐 Streamlit            | Deployment           |

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

This approach can support **personalized marketing, customer engagement, product recommendations, and data-driven sales decisions**.

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
* 🔹 Real-time recommendations

---

## 🚀 From Customer Data to Recommendations

### **Analyze → Learn → Predict → Recommend → Deploy**

---

### ⭐ Thank you for exploring this project!
