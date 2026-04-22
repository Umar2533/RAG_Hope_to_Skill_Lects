# 📚 RAG Pipeline Practice (Data Loading & Text Splitting) $ Semantic Search System using Embeddings $ & Retrievers

This repository contains hands-on practice notebooks for building the foundational components of a **Retrieval-Augmented Generation (RAG)** system using LangChain.
implementation of Retrieval-Augmented Generation (RAG) using semantic search and retrievers. It builds on previous concepts of embeddings and vector databases to create a more advanced and efficient information retrieval system.

---

## 🚀 Project Overview

This project covers two critical steps of any RAG pipeline:

1. **Data Loading** – Importing data from different sources
2. **Text Splitting** – Breaking large text into manageable chunks for embeddings & retrieval
3. **Semantic Search System using Embeddings** - A simple and powerful semantic search system built using embeddings and cosine similarity.
This project demonstrates how to search documents based on meaning (not just keywords).
4. **Implementation of Retrievers & Improving search relevance using RAG**


---

## 📂 Files Included

### 1️⃣ Data Loader Notebook

**File:** `prac_hts_lec5_RAG_DataLoader.ipynb`

#### 🔹 What it covers:

* Loading text using LangChain `Document`
* PDF loading using `pypdf`
* CSV data loading
* Web scraping using `WebBaseLoader`
* Parsing HTML with BeautifulSoup
* Working with multiple URLs
* Introduction to SitemapLoader (reference only)

#### 🔹 Key Concepts:

* `Document` object structure (`page_content`, `metadata`)
* Extracting raw text from different sources
* Preparing data for RAG pipeline

---

### 2️⃣ Data Splitters Notebook

**File:** `prac_hts_lec6_RAG_DataSpliters.ipynb`

#### 🔹 What it covers:

* Splitting large documents into chunks
* Experimenting with different chunk sizes (500, 1000, 1500)
* Understanding chunk overlap
* Using:

  * `RecursiveCharacterTextSplitter`
  * `CharacterTextSplitter`
* Visualizing how text is divided
* 
#### 🔹 Key Concepts:

* Chunk size vs context quality
* Overlap importance for retrieval accuracy
* Token-aware splitting using `tiktoken`
* 
### 3  Embeddings Notebook

**File:** `prac_hts_lec7_RAG_Embeddings.ipynb`
# 🔍 Semantic Search System using Embeddings

A simple and powerful **semantic search system** built using embeddings and cosine similarity.  
This project demonstrates how to search documents based on **meaning (not exact keywords)**.

---

## 🚀 Features

- Convert text into embeddings (vector representation)
- Perform semantic search using cosine similarity
- Retrieve top-k most relevant documents
- Simple and beginner-friendly implementation
- Easily extendable for AI chatbots & LLM apps
- 


## 🛠️ Technologies Used

* Python 🐍
* LangChain
* BeautifulSoup
* PyPDF
* Tiktoken
* NumPy
* Scikit-learn
* Sentence Transformers

**🧠 ** How It Works ** 
Convert all documents into embeddings
Convert user query into embedding
Compute cosine similarity between query & documents
Return top matching results**

**📁 Project Overview**

This project includes:

Embedding generation
Semantic search function
Query testing with different inputs
---

## ⚙️ Installation

Run the following before executing notebooks:

```bash
pip install langchain langchain-community pypdf beautifulsoup4 lxml tiktoken
```

---

## 🧠 Learning Outcomes

After completing these notebooks, you will understand:

* How to load data from multiple sources into LangChain
* How to structure documents for LLM pipelines
* How to split text efficiently for embeddings
* How chunk size and overlap affect retrieval performance
* 

---

## 🔗 Next Steps

These notebooks are part of a larger RAG system. Future steps include:

* Embeddings generation
* Vector database integration (FAISS, Chroma)
* Retrieval optimization
* LLM integration

---

## 📌 Notes

* SitemapLoader is included for reference but not used due to performance constraints
* Chunking strategy directly impacts model performance — experiment wisely
---
💡 **Use Cases**
AI Chatbots
FAQ Systems
Document Search
WhatsApp AI Assistants
Medical / Radiology Report Search
🔮 **Future Improvements**
Add FAISS / Chroma (vector database)
Build FastAPI backend
Integrate with LLMs
Add UI (Streamlit / React)

**LEC 9**

📘 Lecture 9: RAG with Semantic Search & Retrievers

This project demonstrates the implementation of Retrieval-Augmented Generation (RAG) using semantic search and retrievers. It builds on previous concepts of embeddings and vector databases to create a more advanced and efficient information retrieval system.

🚀 What This Project Covers
🔹 Semantic Search using embeddings
🔹 Document indexing and retrieval
🔹 Implementation of Retrievers
🔹 Improving search relevance using RAG
🔹 Query-to-context pipeline
🧠 Key Concepts
1. Semantic Search

Instead of keyword matching, this system finds documents based on meaning using vector embeddings.

2. Retrievers

Retrievers are responsible for:

Fetching the most relevant documents
Reducing irrelevant or redundant results
Improving response quality in RAG systems
3. RAG (Retrieval-Augmented Generation)

Combines:

Retriever (search relevant docs)
LLM (generate answer)
📂 Project Structure
Lecture-9/
│
├── prac_hts_lec9_RAG_Semantic_Search_Retrievers.ipynb
├── data/ (if used)
└── README.md
⚙️ Technologies Used
Python 🐍
Sentence Transformers
Vector Embeddings
(Optional) Qdrant / FAISS
LangChain (if used)
🔍 How It Works
Documents are converted into embeddings
User query is also converted into embedding
Similarity search is performed
Top relevant documents are retrieved
Results can be passed to LLM for final response
▶️ How to Run
Install dependencies:
pip install sentence-transformers
Open Jupyter Notebook:
jupyter notebook
Run:
prac_hts_lec9_RAG_Semantic_Search_Retrievers.ipynb
📌 **Learning Outcome**
Understand how semantic search works
Build a basic RAG pipeline
Use retrievers for better search results
Reduce redundancy in search

**AI Developer | LLM Deployment | Python | FastAPI**
Building intelligent systems using RAG, embeddings, and vector databases

⭐ **Future Improvements**
Add reranking models
Integrate with real LLM APIs
Build production-level RAG system


## 👨‍💻 Author

**DS**
AI Developer | LLM | RAG Systems | Python | FastAPI

---

## ⭐ If you found this helpful

Give this repo a star ⭐ and keep building!

---
