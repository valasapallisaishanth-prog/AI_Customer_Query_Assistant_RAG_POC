AI Customer Query Assistant (RAG POC)
**Project Overview**

This project demonstrates a Retrieval-Augmented Generation (RAG) based AI assistant that answers customer queries using structured FAQ data.

The system uses:

SentenceTransformers for embeddings

FAISS for vector similarity search

Python for preprocessing and retrieval logic

**Objective**

Build a mini AI assistant capable of retrieving relevant answers from structured business FAQ data using semantic search.

**Architecture**

User Query
↓
Convert to Embedding
↓
FAISS Vector Search
↓
Retrieve Most Relevant FAQ
↓
Return Answer

**Dataset**

C4-FAQs dataset from HuggingFace

Converted into structured Question-Answer format

**Technologies Used**

Python

FAISS (Vector Database)

SentenceTransformers

NLP Preprocessing

Google Colab

**How to Run**

Open the notebook in Google Colab

Install dependencies:
pip install -r requirements.txt

Run all cells sequentially

Use interactive input to test queries

**Limitations**

Works only with preloaded FAQ data

No multi-turn conversation support

Answers are directly retrieved (no LLM paraphrasing)

**Future Enhancements**

Integrate HuggingFace LLM for response refinement

Add multi-turn conversation memory

Deploy with Streamlit or Gradio

Support PDF and document ingestion

**IBM-Relevant Skills Demonstrated**

Retrieval-Augmented Generation (RAG)

Vector Search & Semantic Retrieval

NLP Embeddings

Client-oriented AI Solution Design
