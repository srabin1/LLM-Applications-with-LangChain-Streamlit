# LangChain-Based LLM Applications 🚀

This repository presents **multiple Large Language Model (LLM) applications**, following **Udemy GenAI course** ranging from **simple to advanced**, all developed using **LangChain**.  
The projects demonstrate different techniques for building, chaining, and deploying LLM-powered workflows, including **interactive Streamlit applications**.

Each project can be run independently after setting up the environment described below.

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
