# RAG-pdf_chatbot

RAG-pdf_chatbot is an intelligent chatbot system designed to answer questions based on the content of PDF documents. It leverages the cutting-edge Retrieval-Augmented Generation (RAG) architecture, which combines retrieval-based and generation-based approaches to enable efficient and accurate question-answering. By ingesting PDF files, the chatbot can understand and retrieve relevant information from the documents, allowing users to engage in natural language conversations and receive precise responses. This repository provides the implementation of the RAG-pdf_chatbot, including data preprocessing, model training, and deployment scripts. It aims to facilitate information retrieval from PDF documents, enhancing productivity and streamlining research across various domains.

PDF Chatbot with Streamlit
This repository contains a Streamlit application that allows users to upload PDF files and ask questions about their content. The application extracts text from the PDFs, processes it into manageable chunks, stores it in a Chroma vector store, and uses Google's Generative AI to provide answers to user queries.

Features
Upload multiple PDF files
Extract text from PDF files
Chunk the text for better processing
Store text embeddings in a Chroma vector store
Use Google Generative AI to answer questions based on the PDF content
Simple and intuitive Streamlit interface
Requirements
Python 3.8 or higher
Streamlit
PyPDF2
langchain
langchain-google-genai
chromadb
python-dotenv
