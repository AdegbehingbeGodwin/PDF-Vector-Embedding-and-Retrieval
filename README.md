# PDF-Vector-Embedding-and-Retrieval

# PDF Vector Embedding and Retrieval

This project provides a pipeline for extracting text and metadata from PDF documents, converting the content into vector embeddings, and storing them in a FAISS database for efficient similarity-based querying. It is designed to handle large PDFs and supports embedding models from HuggingFace.

## Features

- Extract text and metadata (including images) from PDFs using PyMuPDF.
- Split text into manageable chunks for embedding.
- Generate vector embeddings using HuggingFace models.
- Store and query embeddings in a FAISS database.
- Create a sharable ZIP archive of the vector database.

## Requirements

- Python 3.8 or higher
- Required packages:
  - `PyMuPDF` (`fitz`)
  - `langchain`
  - `langchain-community`
  - `faiss-cpu`
  - `sentence-transformers`

To install the required packages:
```bash
pip install pymupdf langchain langchain-community faiss-cpu sentence-transformers
