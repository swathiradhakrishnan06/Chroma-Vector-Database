# 🧠 Chroma Vector Database 

This repository provides a practical guide to using **ChromaDB**, an open-source embedding-native vector database optimized for LLM and AI applications. The notebook `db.ipynb` demonstrates how to use ChromaDB to store, query, and manage product review data efficiently — complete with metadata and full-text capabilities.

---

## 🔍 What is ChromaDB?

[ChromaDB](https://www.trychroma.com/) is a lightweight, developer-friendly vector database designed for fast retrieval of text embeddings. It supports:
- Native full-text + vector search
- In-memory and persistent storage
- Metadata-based filtering
- Built-in embedding model support or custom embeddings

---

## 📓 What's Inside the Notebook?

The notebook [`db.ipynb`](https://github.com/swathiradhakrishnan06/Chroma-Vector-Database/blob/main/db.ipynb) walks you through the following ChromaDB capabilities:

### ✅ Clients
- Initializing **in-memory** and **persistent** Chroma clients

### ✅ Collections
- Creating and managing document collections

### ✅ Embedding Functions
- Using `sentence-transformers` or default embedding models (optional/customizable)

### ✅ Core Operations
- **Add**: Insert documents with unique IDs and rich metadata  
- **Update**: Modify existing documents by ID  
- **Delete**: Remove documents using IDs or metadata filters  
- **Query**: Retrieve similar documents using vector similarity or keyword match

### ✅ Metadata Filtering
- Filter search results by `product_id`, `category`, `rating`, etc.

### ✅ Full-Text Search
- Query documents using natural language without embeddings

---

## 🚀 Getting Started

### 🔧 Install Dependencies

```bash
pip install chromadb
