# RAG-Based Question Answering System

This is a practice project based on Retrieval-Augmented Generation (RAG) using OpenAI Embeddings, LangChain, and Pinecone Vector Database.

The purpose of this project is to understand how a Question Answering system works with PDF documents by retrieving accurate answers using similarity search instead of generating random responses.

## Project Workflow

PDF Upload → Text Extraction → Text Chunking → Vector Embeddings → Pinecone Storage → Similarity Search → Final Answer Generation

## Features

* PDF document loading and processing
* Text chunking using RecursiveCharacterTextSplitter
* OpenAI Embeddings generation
* Pinecone Vector Database integration
* Similarity search for relevant document retrieval
* RetrievalQA chain for answer generation
* Interactive chatbot loop for user queries

## Technologies Used

* Python
* LangChain
* OpenAI API
* Pinecone
* PyPDF
* Jupyter Notebook
* VS Code

## Required Packages

```bash id="e3p7tk"
pip install langchain
pip install langchain-openai
pip install langchain-pinecone
pip install langchain-community
pip install langchain-core
pip install langchain-text-splitters
pip install pinecone
pip install pypdf
pip install openai
pip install tiktoken
pip install python-dotenv
```

## Environment Variables

Create a `.env` file and add:

```env id="d9s4jq"
OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
```

## Example Query

What is Transformer?

## Example Output

The Transformer is a transduction model that uses self-attention to compute representations of its input and output without using recurrence or convolution.

## Purpose of the Project

This project is created for practice and learning purposes to understand the complete workflow of RAG architecture using vector databases and LLM-based retrieval systems.

It helps in learning how PDF-based intelligent question answering systems are built in real-world AI applications.

## Future Improvements

* Multi-PDF support
* Web interface using Streamlit
* Chat history support
* Source reference display
* Better response optimization

## Author

Md Danish Alam