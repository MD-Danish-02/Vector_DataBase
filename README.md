# RAG Practice: ChromaDB & Pinecone

This repository contains my **practice work on Retrieval-Augmented Generation (RAG)** using LangChain and OpenAI.

In this project, I implemented the same RAG pipeline using **two different vector databases separately**:

* ChromaDB (local)
* Pinecone (cloud)

The goal is to understand how vector databases work in a Question Answering system.

---

## 🚀 What I Practiced

* Loading documents (TXT / PDF)
* Splitting text into chunks
* Creating embeddings using OpenAI
* Storing embeddings in:

  * ChromaDB (local)
  * Pinecone (cloud)
* Retrieving relevant chunks using similarity search
* Generating answers using RetrievalQA

---

## 🔁 Workflow

Documents → Text Splitting → Embeddings → Vector DB → Retrieval → LLM → Answer

---

## 📂 Files in This Repo

* `chroma_db.ipynb` → RAG using ChromaDB (local)
* `pinecone_vector_db.ipynb` → RAG using Pinecone (cloud)

Both notebooks implement the same logic, only the vector database is different.

---

## ⚙️ Key Difference Practiced

**ChromaDB**

* Runs locally
* No API key needed
* Good for testing

**Pinecone**

* Cloud-based
* Requires API key
* Used in production systems

---

## 📦 Required Packages

```bash
pip install langchain
pip install langchain-openai
pip install langchain-community
pip install langchain-text-splitters
pip install chromadb
pip install pinecone
pip install pypdf
pip install openai
pip install tiktoken
pip install python-dotenv
```

---

## 🔐 Environment Variables

Create a `.env` file:

```env
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
```

---

## 💬 Example Queries

* What is artificial intelligence?
* How much funding did Microsoft raise?

---

## 🎯 Purpose

This is a **learning project** to understand:

* How RAG works
* How vector databases store embeddings
* Difference between local and cloud vector databases

---

## 👨‍💻 Author

Md Danish Alam