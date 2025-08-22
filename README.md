# 📘 Watsonx PDF QA Bot

A Retrieval-Augmented Generation (RAG) chatbot powered by **IBM Watsonx foundation models**, **LangChain**, and **Gradio**.  
Upload a PDF, ask questions, and get answers with source references.

---

## 🚀 Features
- PDF document loader (PyPDF)
- Text chunking with LangChain
- Watsonx Granite-3-8B Instruct as LLM
- Watsonx Slate Embeddings + Chroma vector DB
- Gradio UI with tabs (Answer + Sources)

---

## ⚡ Installation

Clone this repo and install dependencies:

```bash
git clone https://github.com/<your-username>/watsonx-rag-pdf-qa.git
cd watsonx-rag-pdf-qa

# create & activate virtual environment (recommended)
python3.11 -m venv .venv
source .venv/bin/activate  # Linux/Mac
.venv\Scripts\activate     # Windows

# install dependencies
pip install -r requirements.txt
