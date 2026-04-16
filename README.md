# 📚 RAG Pipeline Practice (Data Loading & Text Splitting)

This repository contains hands-on practice notebooks for building the foundational components of a **Retrieval-Augmented Generation (RAG)** system using LangChain.

---

## 🚀 Project Overview

This project covers two critical steps of any RAG pipeline:

1. **Data Loading** – Importing data from different sources
2. **Text Splitting** – Breaking large text into manageable chunks for embeddings & retrieval

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

#### 🔹 Key Concepts:

* Chunk size vs context quality
* Overlap importance for retrieval accuracy
* Token-aware splitting using `tiktoken`

---

## 🛠️ Technologies Used

* Python 🐍
* LangChain
* BeautifulSoup
* PyPDF
* Tiktoken

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

## 👨‍💻 Author

**DS**
AI Developer | LLM | RAG Systems | Python | FastAPI

---

## ⭐ If you found this helpful

Give this repo a star ⭐ and keep building!

---
