# 📄 CV Reader – Retrieval-Augmented Generation (RAG)
A Retrieval-Augmented Generation (RAG) based application that ingests CVs (PDFs) and enables intelligent querying using Large Language Models.
The system extracts text from resumes, embeds the content, stores it in a vector database, and retrieves the most relevant information to answer user questions accurately.


#🚀 Features

📥 Upload and parse CVs in PDF format

🔍 Semantic search over CV content

🧠 Context-aware question answering using RAG

📚 Vector-based retrieval for accurate results

⚡ Efficient and lightweight pipeline


#🛠️ Tech Stack

LangChain – RAG orchestration and chaining

LangChain Community – integrations and loaders

ChromaDB – vector database for embeddings

Sentence Transformers – text embedding models

PyPDF – PDF text extraction

Google Generative AI – LLM for answer generation

#🧩 Architecture Overview

Document Loading
CVs are loaded from PDF files and converted into raw text.

Text Chunking
Text is split into manageable chunks for efficient embedding.

Embedding & Storage
Each chunk is embedded using a sentence transformer and stored in ChromaDB.

Retrieval
Relevant chunks are retrieved based on semantic similarity to the user query.

Generation
The retrieved context is passed to a generative model to produce accurate answers.

#📈 Future Improvements

Multi-CV comparison

UI integration (Streamlit / Gradio)

Ranking candidates based on job descriptions

Support for DOCX files
