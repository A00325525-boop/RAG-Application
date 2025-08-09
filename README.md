# RAG-Application
A simple Retrieval-Augmented Generation (RAG) application that can read .txt, .pdf, and .docx files, create embeddings using the Mistral API, store them in an in-memory FAISS vector store, and answer user questions with grounded, context-based responses.

Features
  Multi-format ingestion – Supports .txt, .pdf, .docx files.

  Embeddings with Mistral API – Can be replaced with OpenAI or other embedding providers.

  In-memory FAISS vector store – Fast semantic search.

  Grounded answers – Responses are based only on retrieved context to reduce hallucination.

  Google Colab-ready – No setup required on your local machine.


How It Works
Upload files → .txt, .pdf, or .docx.

Read & chunk text into smaller segments.

Generate embeddings using Mistral API.

Store embeddings in FAISS vector index.

Ask a question → system finds relevant chunks & generates an answer.

Notes
This project is for educational purposes only.

The application is tested with sample marijuana-related documents but works with any topic as long as relevant files are provided.

To avoid hallucinations, answers are strictly based on retrieved document content.

