# 📄 QA System using LangChain + Gemini API

This project is a **Question Answering System (RAG)** using:
- 🧠 [LangChain](https://www.langchain.com/)
- 💬 Google Gemini API (`gemini-1.5-pro`)
- 📦 [ChromaDB](https://www.trychroma.com/)
- 📑 PDF Loader from `langchain_community`

---

## 🚀 Features

✅ Load and split PDF documents  
✅ Embed documents using Gemini's embedding model  
✅ Store vectors using Chroma  
✅ Retrieve relevant chunks using semantic search  
✅ Answer questions using Gemini 1.5 Pro and LangChain RAG chain

---

## 📦 Installation

```bash
pip install -q langchain langchain-community
pip install -q pypdf
pip install -q unstructured
pip install -q langchain-google-genai
pip install -q sentence_transformers
pip install -q langchain-chroma
```
## ⚠️ Quota Limits (Important!)
If you get an error like:

makefile
Copy
Edit
ResourceExhausted: 429 You exceeded your current quota...
You have exceeded your free-tier quota. You can:

Wait until the quota resets (usually every 24 hours)

Use a lighter model (gemini-pro)

Upgrade your billing plan: https://console.cloud.google.com/

Read Gemini quota docs: https://ai.google.dev/gemini-api/docs/rate-limits


## 📌 Credits

LangChain

Google Gemini API

ChromaDB

LangChain Community Loaders

