# PDF-Knowledge-Assistant
The PDF Knowledge Assistant is an AI-powered application that enables users to upload one or multiple PDF documents and ask natural language questions about their content.  Instead of relying only on the Large Language Model's pre-trained knowledge, the application implements Retrieval-Augmented Generation (RAG).

🧠 Project Workflow
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
