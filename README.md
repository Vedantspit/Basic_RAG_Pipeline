# RAG PDF Question Answering System

A simple Retrieval-Augmented Generation (RAG) pipeline built using Python, ChromaDB, Sentence Transformers, LangChain, and Groq.

## Features

- Load PDF documents
- Split documents into chunks
- Generate embeddings using Sentence Transformers
- Store embeddings in ChromaDB
- Retrieve relevant chunks using semantic similarity
- Generate answers using Llama 3.3 via Groq

## Tech Stack

- Python
- LangChain
- ChromaDB
- Sentence Transformers
- Groq API
- PyPDFLoader

## Project Flow

1. Load PDF documents
2. Chunk documents
3. Generate embeddings
4. Store embeddings in ChromaDB
5. Retrieve relevant chunks for a query
6. Pass retrieved context to LLM
7. Generate final response

## Setup

### Clone Repository

```bash
git clone <repo-url>
cd RAG
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Create Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key_here
```

### Run

Open the notebook or execute the Python script.

## Future Improvements

- Streamlit Web UI
- Chat History
- Multi-PDF Support
- Hybrid Search (BM25 + Vector Search)
- Conversation Memory
