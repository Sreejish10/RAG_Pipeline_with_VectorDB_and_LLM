# RAG_Pipeline_with_VectorDB_and_LLM

#  Production RAG Pipeline — Pinecone + Hugging Face + Gemini

An end-to-end Retrieval-Augmented Generation (RAG) pipeline that ingests PDF documents, creates vector embeddings using Hugging Face, stores them in Pinecone, and generates intelligent summaries using Google Gemini.

This project demonstrates a **production-ready semantic search and summarization system** suitable for enterprise document intelligence use cases.

---

##  Architecture Overview
PDF Documents
↓
Document Loader
↓
Text Chunking
↓
Hugging Face Embeddings
↓
Pinecone Vector DB
↓
Semantic Retrieval
↓
Google Gemini LLM
↓
Natural Language Summary


---

## ✨ Features

-  Multi-PDF ingestion
-  Smart recursive chunking
-  Fast batch embedding generation
-  Pinecone serverless vector storage
-  Semantic similarity search
-  Gemini-powered summarization
-  Colab-ready notebook
-  Production-oriented design

---

##  Project Structure
- RAG_Pipeline_with_PineconeVectorDB_and_LLMGemini.ipynb
- VectorDB_docs
- README.md

  
---

##  Tech Stack

- **LangChain** — document loading & splitting  
- **Sentence Transformers** — embeddings (`all-MiniLM-L6-v2`)  
- **Pinecone** — vector database (serverless)  
- **Google Gemini** — LLM summarization  
- **Python / Colab**

---

##  Getting Started

### Clone the Repository






