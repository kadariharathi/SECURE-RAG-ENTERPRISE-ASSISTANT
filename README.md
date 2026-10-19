# Secure Cloud-Based Enterprise Knowledge Assistant

## Overview
A Secure Retrieval-Augmented Generation (RAG) system that helps users retrieve relevant information from enterprise policy documents and generate context-aware answers using Large Language Models (LLMs).

## Features
- PDF document processing and text extraction
- Text chunking and embedding generation
- Semantic search using ChromaDB
- Gemini-powered answer generation
- Streamlit-based user interface
- Designed for enterprise policy knowledge retrieval

## Technologies Used
Python, RAG, Google Gemini, ChromaDB, Sentence Transformers, Streamlit, and PyPDF.

## Project Metrics
- 34 pages of policy documents processed
- 87 text chunks indexed
- 384-dimensional embeddings generated

## How It Works
1. Extract text from PDF documents.
2. Split text into smaller chunks.
3. Generate embeddings for the chunks.
4. Retrieve relevant content using vector search.
5. Generate an answer using the retrieved context and an LLM.

## Setup
1. Clone this repository.
2. Install dependencies with `pip install -r requirements.txt`.
3. Configure your Gemini API key securely using an environment variable or Google Colab Secrets.
4. Run the notebook in Google Colab.

## Security
Never commit API keys, secrets, or confidential documents to GitHub.

## Project Status
Academic and portfolio project. Features and integrations depend on the current implementation in the notebook.
