# RAG and Agents

This repository contains practical implementations and code examples exploring Retrieval-Augmented Generation (RAG) systems and AI agents.

## Project Structure

- **01_Basic_RAG/**
  - `rag_intro.ipynb`: A foundational introduction to RAG workflows using LangChain, HuggingFace embeddings, ChromaDB, and Groq LLMs.

- **02_Chat_with_PDF/**
  - `Chat_with_PDF_RAG.ipynb`: An interactive notebook demonstrating how to load, chunk, and query local PDF documents using `PyPDFLoader`. It utilizes the LLaMA 3 model via Groq API to answer questions strictly based on the provided document context, effectively preventing hallucinations.

##  Getting Started

### Prerequisites
Make sure you have Python installed, then install the required dependencies:
```bash
pip install langchain langchain-core langchain-chroma langchain-huggingface langchain-groq langchain-classic sentence-transformers beautifulsoup4 pypdf