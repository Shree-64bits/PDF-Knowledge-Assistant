# 📚 PDF-Knowledge-Assitant
The PDF Knowledge Assistant is an AI-powered application that enables users to upload one or multiple PDF documents and ask natural language questions about their content.  

Instead of relying only on the Large Language Model's pre-trained knowledge, the application implements Retrieval-Augmented Generation (RAG).Relevant document chunks are retrieved from a vector database and supplied as context to the Gemini LLM, enabling more accurate and context-aware responses. This aligns with the standard LangChain RAG pipeline of loading documents, embedding them into a vector store, retrieving relevant chunks, and providing them to the LLM for grounded answers.

The application is deployed with Gradio, providing an intuitive web interface.

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

```
PDF-RAG-Chatbot/
│
├── Main.ipynb
│
├── requirements.txt
│
├── README.md
│
├── LangChain.pdf(used as a Sample Data
│     
└─── screenshots/
      ├── upload.png
      ├── question.png
      ├── answer.png


```
---

## Future Improvements

- Multi-document search
- OCR support for scanned PDFs
- Conversation memory
- Hybrid Search (BM25 + Dense Retrieval)
- ChromaDB support
- Hugging Face deployment
- Citation highlighting

---
# 📜 License

This project is open-source and intended for educational and learning purposes.

---

## Connect With Me

**Shree Sharma**

LinkedIn: *(https://www.linkedin.com/in/shree-sharma-8b879a324?utm_source=share_via&utm_content=profile&utm_medium=member_android)*
