# 📊 Customer Churn Prediction — Classification & Regression  
Machine Learning • Deep Learning • Streamlit Web Applications  

## 📌 Overview  
This repository contains end-to-end machine learning workflows for **Customer Churn Modeling**.  
The dataset includes detailed information about a bank’s customers, with a target variable indicating whether the customer has **churned** (closed their account) or continues to remain with the bank.

This project includes:

- 🧠 **Churn Classification Model** (Deep Learning)
- 📈 **Churn Regression Model** (Predicting churn probability score)
- 🎛️ **Hyperparameter tuning notebooks**
- 🌐 **Two Streamlit web applications**
- 💾 Saved models, encoders, and scalers

---

## 🧠 Models Developed  

### **1️⃣ Classification Model — Will the Customer Churn?**  
A deep learning binary classifier built with:

- Keras/TensorFlow  
- Label Encoding (Gender)  
- One-Hot Encoding (Geography)  
- Standard Scaling  
- Optimized hyperparameters  

**Output:**  
- `0` → Customer stays  
- `1` → Customer churns  

🔗 **Live Streamlit App:**  
https://deeplearninggit-6mff75dautru3heuzrkdeg.streamlit.app/

---

### **2️⃣ Regression Model — Churn Probability Score**  
This model predicts a **continuous churn probability**, allowing for fine-grained risk assessment.

🔗 **Live Streamlit App:**  
https://deeplearninggit-mbgwgidkualfm95op3fghx.streamlit.app/

---

## 🌐 Streamlit Applications  
Both apps include:

- User-friendly interface  
- Automatic preprocessing using saved pickle encoders  
- Real-time churn prediction  
- Deployment via Streamlit Cloud  

### **Run locally:**

```bash
pip install -r requirements.txt
streamlit run classification_app.py
# or
streamlit run regression_app.py
```

