# 🚀 ChatGroq RAG Chatbot with Streamlit

## 📌 Project Overview
This project builds a *Retrieval-Augmented Generation (RAG) chatbot* using *ChatGroq (LLaMA3), **LangChain, **OpenAI embeddings, and **Streamlit UI*.

The chatbot:
- Loads documents (TXT/PDF)
- Splits them into chunks
- Generates embeddings
- Stores them in FAISS vector database
- Retrieves relevant context
- Generates answers using Groq LLM
- Maintains chat history

---

## 🛠️ Tech Stack
- LLM: ChatGroq (LLaMA3)
- Framework: LangChain
- Embeddings: OpenAI
- Vector Store: FAISS
- UI: Streamlit

---

## ⚙️ Setup Instructions

### Install Dependencies
```bash
pip install langchain langchain-community langchain-groq openai faiss-cpu streamlit python-dotenv
