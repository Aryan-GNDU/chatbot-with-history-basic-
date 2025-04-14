# 🧠 Context-Aware Query Bot using LLMs & Vector Databases

This repository showcases a project built around the concept of **contextual awareness** in AI. It combines semantic search, document understanding, and intelligent LLM-based responses to simulate a smart assistant capable of understanding user intent and retrieving contextually relevant information.

## 🌟 Key Highlight

### 🔑 Contextual Awareness
The core goal of this project is to **learn and implement contextual awareness**—enabling an AI system to understand the *context* behind a user's query and provide accurate, relevant responses using memory and vector embeddings.

## 📁 Files Overview

### 1. `bot.ipynb`
Acts as the main chatbot interface. It routes user queries, performs intent classification, and calls the appropriate retrieval logic. It integrates with a language model to respond intelligently, using external context.

### 2. `vector_retireivevr.ipynb`
Handles the vector retrieval pipeline:
- Loads and embeds documents
- Stores embeddings in a vector database
- Performs similarity search to retrieve relevant information for a given query

## 🚀 Features

- 🧠 **Contextual Awareness** (Core focus!)
- 🔍 **Semantic Search:** Retrieves meaning-based matches using embeddings
- 🤖 **LLM Integration:** Handles intelligent response generation
- 📄 **Custom Document Search:** Ingests PDFs, TXT, and more
- ⚙️ **Modular Pipeline:** Separate workflows for embedding and querying

## 🛠️ Technologies Used

- Python
- Jupyter Notebooks
- LangChain or custom logic
- Vector DB (e.g., Pinecone, FAISS)
- Hugging Face Transformers / OpenAI LLMs

