# 📄 NVIDIA NIM–Powered Document Question Answering (RAG)

This repository contains a **Retrieval-Augmented Generation (RAG)** application that allows users to **ask natural-language questions about a collection of documents (PDFs)** and receive **context-grounded answers** powered by **NVIDIA NIM**, **LangChain**, and **FAISS**.

The application is built with **Streamlit** and deployed on **Streamlit Cloud** for easy interaction.

---

## 🚀 Features

- 📚 Document ingestion from a local PDF directory  
- ✂️ Text chunking with overlap for better retrieval  
- 🔍 Semantic search using NVIDIA embeddings  
- 🧠 Context-aware answers using NVIDIA NIM LLMs  
- ⚡ FAISS vector store for fast similarity search  
- 🖥️ Interactive Streamlit UI  
- 🔐 Per-session API key handling (no hard-coded secrets)

---

## 🧠 Architecture Overview

```text
PDFs → Text Splitter → NVIDIA Embeddings → FAISS Vector Store
                                   ↓
                            Retriever
                                   ↓
                         NVIDIA NIM LLM
                                   ↓
                         Context-grounded Answer
```
- ⚡Link to Streamlit app:
- RAG-Based PDF Question Answering with NVIDIA NIM:
   [NVIDIA_NIM RAG Chatbot](https://questionanswerconversationalchatbot-hyeih44pod9eudc4qewmsn.streamlit.app/)
