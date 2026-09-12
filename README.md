# GenAI PDF Assistant

A PDF-based Retrieval-Augmented Generation (RAG) chatbot that allows users to upload PDF documents and ask questions using natural language.

The application uses document embeddings, semantic similarity search, LangChain, Groq LLM, and Streamlit to generate answers grounded in the uploaded documents.

## Features

- Upload one or multiple PDF documents
- Extract text from PDF files
- Split documents into smaller chunks
- Generate vector embeddings for document chunks
- Perform semantic similarity search
- Retrieve relevant document context
- Generate context-aware answers using an LLM
- Conversational chat interface
- Agent-based document retrieval
- Streamlit-based user interface

## Architecture

```text
                 PDF Documents
                       |
                       v
                PDF Text Extraction
                       |
                       v
                 Text Chunking
                       |
                       v
              Document Embeddings
                       |
                       v
                Vector Database
                       |
                       v
                 User Question
                       |
                       v
              Semantic Retrieval
                       |
                       v
               Relevant Context
                       |
                       v
                  Groq LLM
                       |
                       v
                  Final Answer
