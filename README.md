
# 📄 PDF Whisperer – Chat with your PDFs using Gemini 🤖

**PDF Whisperer** is an interactive Streamlit web app that lets you upload one or more PDF documents and ask questions about their content. Powered by Google's Gemini (Gemini 1.5 Flash) and LangChain, it provides accurate answers by reading and understanding your files using retrieval-augmented generation (RAG).

---

## 🚀 Demo

[![Open in Streamlit](https://pdf-whisperer-fbbx9xxfod6s55ywtyaqnt.streamlit.app/)

---

## 🧠 Features

- 📁 Upload multiple PDFs
- 🔍 Semantic search using vector embeddings
- 💬 Ask natural language questions
- 🤖 Powered by Google Gemini 1.5 Flash & LangChain
- 🧠 Uses FAISS vector database

---

## 🛠️ Tech Stack

- [Streamlit](https://streamlit.io/) – Web interface  
- [LangChain](https://python.langchain.com/) – Framework for LLM chains  
- [Google Generative AI (Gemini)](https://ai.google.dev/) – LLM provider  
- [FAISS](https://github.com/facebookresearch/faiss) – Vector similarity search  
- [PyPDF2](https://pypi.org/project/PyPDF2/) – PDF reading

---

## 📦 Installation

```bash
git clone https://github.com/your-username/pdf-whisperer.git
cd pdf-whisperer
pip install -r requirements.txt
