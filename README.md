# Multi Document RAG Chatbot

## 📌 Project Overview

The **Multi Document RAG Chatbot** is an AI-powered document question-answering system that allows users to upload multiple documents and interact with them through a conversational chat interface. The system uses **Retrieval-Augmented Generation (RAG)** to retrieve relevant information from uploaded documents and generate accurate, context-based answers using Large Language Models.

This project is designed to reduce the time and effort required to manually read and search through large documents such as PDFs, reports, research papers, legal documents, and technical manuals.

---

## 🚀 Features

- Upload and analyze multiple documents
- Supports file formats such as PDF, DOCX, TXT, and CSV
- Natural language question-answering interface
- Retrieval-Augmented Generation based response generation
- Semantic search using vector embeddings
- Context-aware answers generated using LLMs
- Source-based response generation for better reliability
- User-friendly Streamlit interface
- Suitable for students, researchers, professionals, and enterprises

---

## 🧠 How It Works

1. Users upload documents through the Streamlit interface.
2. The system extracts text from the uploaded files.
3. Extracted text is split into smaller meaningful chunks.
4. Vector embeddings are generated for each chunk.
5. Embeddings are stored in a vector database such as FAISS or Chroma.
6. When a user asks a question, the query is converted into an embedding.
7. Relevant document chunks are retrieved using semantic similarity.
8. The retrieved context is passed to an LLM.
9. The chatbot generates a grounded and meaningful answer.

---

## 🛠️ Technology Stack

### Frontend
- Streamlit

### Backend
- Python
- LangChain

### Document Processing
- PyMuPDF
- python-docx

### Vector Database
- FAISS / Chroma

### Embedding Models
- HuggingFace Sentence Transformers
- OpenAI Embeddings

### Language Models
- OpenAI GPT
- LLaMA / Mistral or other open-source LLMs

### Development Tools
- Visual Studio Code
- Jupyter Notebook

---

## 📂 Supported Document Types

- PDF
- DOCX
- TXT
- CSV

---

## 📊 System Architecture

The system follows a modular architecture consisting of the following components:

- Document Upload Module
- Text Extraction Module
- Text Chunking Module
- Embedding Generation Module
- Vector Store Module
- Semantic Retrieval Module
- LLM Answer Generation Module
- Streamlit Chat Interface

This architecture makes the system scalable, flexible, and suitable for future improvements.

---

## 📸 Output Screenshots

### Document Upload and Management Interface

This interface allows users to upload documents through a simple drag-and-drop or browse option. Once uploaded, the document is displayed with its name and size.

### Chat and Document Analysis Interface

After uploading a document, users can ask questions, choose response language, select complexity level, and use suggested prompts for quick analysis.

### RAG-Based Answer Generation

The chatbot retrieves relevant chunks from uploaded documents and generates accurate answers using the selected language model.

---

## 🎯 Project Objectives

- To develop an intelligent multi-document question-answering system using RAG.
- To reduce manual document reading effort.
- To support multiple document formats.
- To apply semantic search for better retrieval.
- To generate accurate and context-aware answers using LLMs.
- To provide a simple and interactive chat interface.
- To improve accessibility of document-based knowledge.

---

## ✅ Applications

- Academic document analysis
- Research paper summarization
- Legal document understanding
- Technical manual search
- Enterprise knowledge management
- Report analysis
- Student study assistance

---

## 🔮 Future Enhancements

- Support for Excel, HTML, and scanned image-based PDFs
- OCR support for image-based documents
- Multilingual document and query support
- Multi-turn conversation memory
- Document summarization feature
- Role-based access control
- Cloud-based vector database integration
- Fine-tuned domain-specific LLM support
- Improved source citation and verification

---

## 📌 Conclusion

The Multi Document RAG Chatbot provides an efficient and intelligent way to interact with large document collections. By combining semantic search, vector embeddings, and large language models, the system delivers accurate and context-grounded responses. It helps users save time, reduce manual effort, and access document knowledge through a simple conversational interface.

---

## 👩‍💻 Team Members

- Dhanushree S  
- Jahanavi M  
- Siri M  
- Jeevika Reddy K  

---

## 🏫 Institution

Department of Computer Science and Engineering (Data Science)  
Vemana Institute of Technology, Bengaluru  
Visvesvaraya Technological University  
Academic Year: 2025–2026
