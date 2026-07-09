# PDF Chatbot with Langflow

A RAG (Retrieval-Augmented Generation) chatbot built in Langflow that answers questions about uploaded PDF documents. Uses OpenAI embeddings, ChromaDB for vector storage, and GPT for generating answers based on retrieved document content.

## How it works
- Reads and chunks PDF files
- Generates embeddings and stores them in a Chroma vector database
- Retrieves relevant chunks based on user questions
- Passes context + question to an LLM to generate accurate answers
