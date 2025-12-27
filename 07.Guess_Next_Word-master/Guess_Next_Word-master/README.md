# 📚 Guess Next Word — LSTM Language Model

A deep learning project that uses an **LSTM (Long Short-Term Memory)** neural network to predict the **next word** in a sequence of text. The repository includes preprocessing scripts, model's script named experiments, trained models, tokenizer, and a Streamlit app for interactive predictions.

---

## 🚀 Project Overview

This project demonstrates how recurrent neural networks learn language structure and generate the most probable next word. Using **Hamlet.txt** as the training dataset, the workflow includes:

- Text cleaning and tokenization  
- Creating incremental n-gram sequences  
- Word embedding with Keras `Embedding` layer  
- LSTM-based and GRU sequence model for next-word prediction  
- Model training and evaluation  
- Streamlit interface for real-time word prediction

---

## 🧠 Model Architecture

The neural network consists of:

1. **Embedding Layer** – Converts words into 100-dimensional vectors  
2. **LSTM Layers** – Captures context and temporal relationships in text  
3. **Dense Softmax Output** – Predicts the next likely word from the vocabulary  

The repository contains both `.h5` (legacy) and `.keras` (recommended) model formats.

---

## 🌐 Live Demo (Streamlit Cloud)

Try the interactive next-word prediction app here:

👉 https://guessnextword-fbzugxpbpwfmic7rqu2h9a.streamlit.app/

No installation needed — just type a phrase and the model will predict the next word.
---


### 1️⃣ Clone the Repository
```bash
git clone https://github.com/srabin1/Guess_Next_Word.git
cd Guess_Next_Word
```
### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 3️⃣ Run the Streamlit App locally
```bash
streamlit run app.py
```



