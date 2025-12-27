v# 🏥 Medical Chatbot – Intelligent PDF-Based Healthcare Question Answering System

The **Medical Chatbot** is an advanced AI-powered question-answering system designed to retrieve meaningful, accurate, and context-aware responses from medical PDF documents. By combining Natural Language Processing (NLP), vector search, and large language models, this system enables users to ask healthcare-related queries and receive precise answers extracted directly from trusted document sources.

---

## 🌟 Project Overview

This project processes medical PDF files by converting them into structured text chunks, embedding them using state-of-the-art models, and storing them in a highly efficient vector database. When a user submits a question, the system performs semantic similarity search, retrieves the most relevant document segments, and generates a clear and contextually reliable answer using a powerful language model.  

It ensures:
- Contextual understanding of medical content  
- Efficient document retrieval  
- Consistent and reliable responses  
- Seamless user interaction  

---

## ✨ Key Features

### 🧠 Intelligent Knowledge Extraction
- Converts PDFs into searchable knowledge segments  
- Uses embeddings for deep semantic understanding  
- Retrieves only the most relevant medical insights  

### 🤖 Advanced Question-Answering
- Understands user intent  
- Generates accurate and concise responses  
- Uses predefined medical-safe prompting  

### ⚡ High Performance & Scalability
- Fast similarity search through Pinecone
- Optimized for large document collections
- Designed for real-time response delivery  

### 👩‍⚕️ Healthcare Focused
- Suitable for medical learning, reference, and support
- Assists with document understanding and knowledge lookup
- Supports structured medical knowledge workflows  

---

## 🛠️ Built With
- **Python**
- **LangChain**
- **Flask**
- **Meta Llama 2**
- **Pinecone**
- **Hugging Face Embeddings**

---

## 🚀 System Flow
1️⃣ Upload medical PDF documents  
2️⃣ PDFs are split into manageable text chunks  
3️⃣ Text is converted to embeddings  
4️⃣ Embeddings are indexed in Pinecone  
5️⃣ User submits a query  
6️⃣ Top-matching text chunks are retrieved  
7️⃣ The language model generates the final answer  

---

## 🔐 API & Credentials
Use a `.env` file to securely configure:
- Pinecone API Key
- Pinecone Environment
- Model configuration details  

---

## 🧪 Use Cases
- Medical research assistance  
- Healthcare learning & knowledge support  
- Clinical document understanding  
- Medical training & education tools  

