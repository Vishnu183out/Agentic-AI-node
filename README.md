
# Agentic-AI-node

#  Agentic AI - Node.js Server for AEM Integration

This is a Node.js backend server built to integrate with Adobe Experience Manager (AEM) using **Agentic AI + RAG** architecture. It allows ingestion of AEM content, vectorization (embedding), and querying using a large language model (LLM).

## Features

- Fetch content from AEM
- Generate embeddings using OpenAI (or any LLM)
- Store vectors in Pinecone (or other vector DBs)
- Query relevant documents using RAG
- CORS-enabled to allow frontend (e.g. AEM) interaction

---

## Requirements

- Node.js (v18 or above recommended)
- An OpenAI API key (for embedding + querying)
- Pinecone account 

---

## 🛠 clone repository


Step 1. git clone https://github.com/Vishnu183out/Agentic-AI-node.git

Step 2. npm install

step 3. Create a .env file
Inside the root folder, create a .env file and add the following variables:

env

OPENAI_API_KEY=your_openai_api_key
PINECONE_API_KEY=your_pinecone_api_key
PINECONE_ENVIRONMENT=your_pinecone_environment
PINECONE_INDEX=your_pinecone_index



