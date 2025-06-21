# 🧠 Retrieval-Augmented Generation (RAG) Pipeline with OpenAI & ChromaDB

This project implements a simple but complete Retrieval-Augmented Generation (RAG) pipeline using Python. It takes a PDF document, splits it into text chunks, embeds those chunks using OpenAI embeddings, and stores them in ChromaDB for fast semantic retrieval.

## 🚀 Features

- 📄 PDF document ingestion
- ✂️ Text chunking using LangChain’s `RecursiveCharacterTextSplitter`
- 🔍 OpenAI embedding generation
- 💾 Vector storage using ChromaDB
- ✅ Ready for Retrieval-Augmented Generation (RAG) tasks

---

## 🧰 Tech Stack

- **LangChain**
- **OpenAI API**
- **ChromaDB**
- **PyPDF / pdfplumber / PyMuPDF** (for PDF reading)
- **dotenv** (for environment variable management)

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/rag-pipeline-openai-chromadb.git
cd rag-pipeline-openai-chromadb
pip install -r requirements.txt
