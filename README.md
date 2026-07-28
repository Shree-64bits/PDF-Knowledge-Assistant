# PDF-Knowledge-Assistant
The PDF Knowledge Assistant is an AI-powered application that enables users to upload one or multiple PDF documents and ask natural language questions about their content.  Instead of relying only on the Large Language Model's pre-trained knowledge, the application implements Retrieval-Augmented Generation (RAG).

---

## 🚀 Features

- Upload one or more PDF documents
- Automatic text extraction using PyMuPDF
- Intelligent document chunking with overlap
- Semantic embeddings using Sentence Transformers
- Fast vector similarity search with FAISS
- Context-aware answer generation using Google Gemini
- Source citation with retrieved document pages
- Interactive Gradio web interface

---

## 🛠️ Technologies Used

- Python
- Google Gemini API
- Sentence Transformers
- FAISS
- PyMuPDF
- NumPy
- Gradio

---

## 📂 Project Workflow

```
User Uploads PDF
        │
        ▼
Extract Text from PDF
        │
        ▼
Split into Chunks
        │
        ▼
Generate Embeddings
        │
        ▼
Store in Vector Database
        │
        ▼
User asks Question
        │
        ▼
Semantic Similarity Search
        │
        ▼
Relevant Chunks Retrieved
        │
        ▼
Prompt + Context sent to Gemini
        │
        ▼
Gemini Generates Answer
        │
        ▼
Display Response in Gradio 
```

---

## 📸 Screenshots

### Upload PDF

![Upload](assets/screenshot1.png)

---

### Ask Questions

![Question](assets/screenshot2.png)

---

### Generated Answer

![Answer](assets/screenshot3.png)

---


## Example Questions

- What is LangChain?
- Explain RAG.
- What are the core components?
- Summarize this document.
- What is LangGraph?

---

## Project Architecture

![Architecture](assets/architecture.png)

---

## Future Improvements

- Multi-document search
- OCR support for scanned PDFs
- Conversation memory
- Hybrid Search (BM25 + Dense Retrieval)
- ChromaDB support
- Streamlit deployment
- Hugging Face deployment
- Citation highlighting

---
# 📜 License

This project is open-source and intended for educational and learning purposes.

---

## Connect With Me

**Shree Sharma**

LinkedIn: *(https://www.linkedin.com/in/shree-sharma-8b879a324?utm_source=share_via&utm_content=profile&utm_medium=member_android)*


---

GitHub:
(Add your GitHub)
