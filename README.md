# RAG PDF Chatbot (Streamlit + LangChain + Groq)

This project is a Retrieval-Augmented Generation (RAG) chatbot built with Streamlit. It uses Groq's LLaMA model and LangChain to answer questions based on content from a local PDF file (`reflexion.pdf`).

## Features

- Loads and indexes a PDF using LangChain
- Uses Hugging Face MiniLM for text embeddings
- Stores chunks in a FAISS vector database
- Answers user questions using Groq’s LLaMA model
- Interactive Streamlit chat interface
