# RAG-Powered-Legal-Knowledge-Base

# Legal Contract RAG & Clause Search System

A Retrieval-Augmented Generation (RAG) system built with LangChain, ChromaDB, and Google Gemini to enable semantic search and precise question answering across legal contracts and compliance documents.

## 📌 Features

* **Document Ingestion & Chunking:** Processes legal agreements using `RecursiveCharacterTextSplitter` to maintain structural context.
* **Vector Embeddings & Storage:** Generates vector representations via `gemini-embedding-001` and indexes text chunks in **ChromaDB** for similarity search.
* **Contextual Answer Generation:** Utilizes **Google Gemini (`gemini-3.8-flash`)** to answer natural language queries using *only* retrieved document contexts, preventing hallucinations.
* **Low Latency Retrieval:** Fetches top matching document fragments in milliseconds based on vector similarity.


## 🛠️ Tech Stack

* **Language:** Python
* **Orchestration Framework:** LangChain (`langchain-google-genai`, `langchain-community`, `langchain-core`)
* **Vector Store:** ChromaDB
* **Embeddings:** Google Generative AI Embeddings (`gemini-embedding-001`)
* **LLM Engine:** Google Gemini (`gemini-3.8-flash`)
* **Environment:** Google Colab

