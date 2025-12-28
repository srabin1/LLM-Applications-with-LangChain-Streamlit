# Simple GenAI RAG App (LangChain + FAISS + OpenAI)

This project is a minimal **Retrieval-Augmented Generation (RAG)** example using **LangChain**.  
It scrapes a webpage (LangChain docs), splits it into chunks, embeds the chunks, stores them in a **FAISS** vector database, and answers questions using a **retrieval chain**.

## What it does
1. **Load data** from a website (web scraping)
2. Convert the page into **LangChain Documents**
3. Split the text into **chunks**
4. Convert chunks into **vector embeddings** (OpenAI embeddings)
5. Store vectors in a **FAISS** vector store
6. Use a **retriever + LLM** to answer questions based only on retrieved context

## Requirements
- Python 3.9+
- An OpenAI API key
- (Optional) LangSmith key for tracing

Suggested packages:
- `langchain`, `langchain-community`, `langchain-openai`, `langchain-text-splitters`
- `faiss-cpu`
- `python-dotenv`

