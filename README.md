# AI Claim Assistant – Insurance RAG System

## 🚀 Overview

AI-powered insurance claim processing system built using FastAPI and Retrieval-Augmented Generation (RAG). The system automates document validation and performs intelligent claim analysis using semantic search.

## ✨ Features

* 📄 Document ingestion pipeline for policy and claim documents
* 🔍 Embedding-based semantic search for clause retrieval
* 🤖 AI-driven claim analysis using RAG
* ⚡ FastAPI-based scalable REST APIs
* 📊 Real-time document processing and inference

## 🛠️ Tech Stack

* Python
* FastAPI
* NLP / RAG
* Embeddings (FAISS / OpenAI / HuggingFace)
* REST APIs

## 🏗️ Architecture

1. Upload claim + policy documents
2. Generate embeddings
3. Store in vector database
4. Retrieve relevant clauses
5. Generate AI-based decision

## ▶️ How to Run

```bash
git clone https://github.com/your-username/ai-claim-assistant-rag
cd ai-claim-assistant-rag
pip install -r requirements.txt
uvicorn app.main:app --reload
```

## 📌 Future Improvements

* Add frontend dashboard
* Improve model accuracy
* Deploy using Docker / Cloud

## 👩‍💻 Author

Prarthana Khairnar
