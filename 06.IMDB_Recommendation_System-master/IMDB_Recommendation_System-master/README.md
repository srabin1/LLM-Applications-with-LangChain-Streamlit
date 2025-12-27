# ⭐ IMDB Recommendation System — Simple RNN Model

This project implements a **Simple Recurrent Neural Network (RNN)** to build a sentiment-based recommendation/prediction system using the **IMDB movie review dataset**.  
The trained model is deployed as an interactive **Streamlit web application**.

🔗 **Live Web App:**  
https://imdbrecommendationsystem-56lwypjqhkah7uvsyxfjap.streamlit.app/

---

## 📌 Project Overview

This repository contains:

- A **SimpleRNN model** trained on IMDB movie reviews  
- Scripts for text preprocessing, model training, and prediction  
- A Streamlit app for real-time movie review classification  
- Saved trained model file (`simple_rnn_imdb.h5`)  
- Jupyter notebooks for exploration and experimentation

The goal is to demonstrate how deep learning can classify text reviews as **positive** or **negative**, forming the basis of a recommendation or sentiment analysis system.

---


## 🚀 How to Run Locally

### **1. Clone the repository**
```bash
git clone https://github.com/<your-username>/IMDB_Recommendation_System.git
cd IMDB_Recommendation_System
```

### **2. Install dependencies**
```bash
pip install -r requirements.txt
```

### **3. Run the Streamlit App**
```bash
streamlit run main.py
```
