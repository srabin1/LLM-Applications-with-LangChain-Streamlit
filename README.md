# LangChain-Based LLM Applications 🚀

This repository presents **multiple Large Language Model (LLM) applications**, following online resources including **Udemy GenAI course** ranging from **simple to advanced**, all developed using **LangChain**.  
The projects demonstrate different techniques for building, chaining, and deploying LLM-powered workflows, including **interactive Streamlit applications**.

Each project can be run independently after setting up the environment described below.

To view the online app and demo for each project, please check the corresponding subfolders and the provided links.

---

## 📂 Repository Overview

- Multiple LLM applications in separate folders
- Projects range from beginner-level to advanced use cases
- Built using LangChain with support for Streamlit-based deployment

---

## ⚙️ Environment Setup (Required)

All projects are designed to run with **Python 3.11**.

### 1️⃣ Create a Conda Environment

Run the following command from the root directory:

```bash
conda create -p venv python==3.11 -y
```
### 2️⃣ Activate the Environment

```bash
conda activate venv/
```
### 📦 Install Required Packages

Install all dependencies using the provided requirements.txt file:

```bash
pip install -r requirements.txt
```

---
### 🧠 VS Code Kernel Configuration

To ensure the correct Python environment is used:

Open the desired project folder in Visual Studio Code

Click “Select Kernel” in the top-right corner

Choose:
```bash
venv (Python 3.11)
```
---
### 🔑 API Keys & Environment Variables

Some applications (especially Streamlit apps) require API keys from external services.

Required Accounts: You must create accounts and generate API keys from:

OpenAI

LangChain

Hugging Face

#### Configure .env File

1. Create a .env file in the project directory

2. Replace the placeholder values with your own API keys:

```bash
OPENAI_API_KEY=*****
LANGCHAIN_API_KEY=*****
HUGGINGFACE_API_KEY=*****
```

### ⚠️ Important:
Do NOT commit your .env file to GitHub. Add it to .gitignore.

---
### ▶️ Running Streamlit Applications

Navigate to the desired project folder and run:
```bash
streamlit run app.py
```
---

### 🛠 Technologies Used

Python 3.11

LangChain

OpenAI API

Hugging Face

Streamlit

VS Code

Conda

---
### ▶️ Live Demo
1. Customer Churn Prediction — Classification:
   [Churn Classification](https://deeplearninggit-6mff75dautru3heuzrkdeg.streamlit.app/)

2. Customer Churn Prediction — Regression:
   [Churn Regression](https://deeplearninggit-mbgwgidkualfm95op3fghx.streamlit.app/)

3. IMDB Recommendation System — Simple RNN Model:
   [IMDB Recommendation System](https://imdbrecommendationsystem-56lwypjqhkah7uvsyxfjap.streamlit.app/)

4. Guess Next Word — LSTM Language Model:
   [LSTM Language Model](https://guessnextword-fbzugxpbpwfmic7rqu2h9a.streamlit.app/)
   
5. RAG Document Q&A With Groq:
   [RAG Document Q&A With Groq](https://questionanswerconversationalchatbot-znkeatp8cuoutfmvcekjj9.streamlit.app/)

6. Enhanced Q&A Chatbot With OpenAI:
   [Enhanced Q&A Chatbot With OpenAI](https://questionanswerconversationalchatbot-2jvydeqfojelumoljvmfhy.streamlit.app/)

7. Upload your PDF and ask any question about it:
   [Conversational RAG with PDF uploads and chat history](https://questionanswerconversationalchatbot-jaqzeetl5eanmggzk2iyzw.streamlit.app/)

8. This is a search engine, ask anything from Wikipedia or Arxive websites:
   [LangChain-Chat with search](https://questionanswerconversationalchatbot-g48wy7tukjf7dtvkqpse7x.streamlit.app/)

9. Upload your SQL Database and ask any question:
   [LangChain: Chat with SQL DB](https://questionanswerconversationalchatbot-ks3mf82qbtxwj3ttr8v9jk.streamlit.app/)

10. RAG Document Q&A With HuggingFace Embeddings:
   [RAG Document Q&A With HuggingFace Embeddings](https://questionanswerconversationalchatbot-ednd455mduvxpo89b2wzxr.streamlit.app/)

11. Summarize Texts from YouTube channel or any other websites:
   [Text Summary](https://questionanswerconversationalchatbot-svua2cflnhymvotbxfxavi.streamlit.app/)

12. Text To Math Problem Solver Using Groq models:
   [Math Chatbot](https://questionanswerconversationalchatbot-b7jptkss6xnqjuqesvzuym.streamlit.app/)

13. RAG-Based PDF Question Answering with NVIDIA NIM:
   [NVIDIA_NIM RAG Chatbot](https://questionanswerconversationalchatbot-hyeih44pod9eudc4qewmsn.streamlit.app/)


