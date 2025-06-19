# Langchain-Data-Ingestion-and-Text-splitting
# 🔍 LangChain Data Ingestion & Text Splitting for RAG Pipelines

This repository demonstrates the core components of a Retrieval-Augmented Generation (RAG) system using [LangChain](https://github.com/langchain-ai/langchain). The focus is on **data ingestion** and **text splitting**, which are essential for preparing documents for semantic search and question-answering applications.

---

## 🚀 Overview

Retrieval-Augmented Generation (RAG) is a hybrid NLP architecture that combines:
- Information retrieval from a knowledge base (vector store)
- Large Language Model (LLM) generation using retrieved data

To enable this, we first need to ingest documents, clean and split them, and store them efficiently. This project focuses on:

✅ Document ingestion (text, PDFs, XML, etc.)  
✅ Text splitting using LangChain’s utilities  
✅ Preparing the documents for downstream use in vector databases or retrieval systems.

---

## 📁 Project Structure

```bash
Langchain-Data-Ingestion-and-Text-splitting/
├── DataIngestion.ipynb       # Notebook for loading and cleaning data
├── TextSplitter.ipynb        # Notebook for chunking text using LangChain
├── attention.pdf             # Sample PDF document
├── records.xml               # Sample XML document
├── speech.txt                # Sample plain text document
├── requirements.txt          # Python dependencies
├── test_langsmith.py         # Test script using LangSmith for tracing/debugging
├── .env                      # (Optional) Environment variables (ignored by Git)
├── README.md                 # You're reading it!
