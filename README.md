<div align="center">🦜🔗 LangChain Models ExplorerA high-performance repository demonstrating the Model I/O layer of LangChain using OpenAI and Hugging Face.</div>📖 


Overviewlangchain-models is a curated collection of Python implementations designed to master the Model I/O component of the LangChain ecosystem. This repository serves as a bridge between raw data and semantic intelligence, showcasing how to leverage industry-leading LLMs and local embedding models.From simple text completions to complex Semantic Search systems, this project provides a modular approach to understanding AI model integration.


🚀 Key Features:
🤖 LLM Mastery: Direct integration with Large Language Models for deterministic text generation.
💬 Structured Conversations: Advanced chat interfaces using System, Human, and AI message schemas.
🔍 Semantic Intelligence: Generating high-dimensional vector embeddings using OpenAI’s text-embedding-3-large.
📊 Vector Similarity: Implementing Cosine Similarity to perform semantic search across custom datasets (e.g., Cricketer profiles).
🌐 Hybrid Approach: Seamlessly switching between cloud-based (OpenAI) and local (Hugging Face) models.
🗂️ Project StructureThe architecture follows a clean, numbered organization for step-by-step learning:


📦 langchain-models:
 ┣ 📂 1.LLMs/                # Basic Large Language Model implementations
 ┣ 📂 2.ChatModels/          # Conversational schemas and Chat-based logic
 ┣ 📂 3.EmbeddedModels/      # The core of Semantic Search & Vector Analysis
 ┃ ┣ 📜 1_embedding_openai_query.py
 ┃ ┣ 📜 2_embedding_openai_docs.py
 ┃ ┣ 📜 3_embedding_hf_local.py
 ┃ ┗ 📜 4_document_similarity.py    # Main script for Semantic Search (Cricketers Dataset)
 ┣ 📜 .env                   # Configuration & API Keys (Strictly Git-ignored)
 ┣ 📜 .gitignore             # Protection against secret leaks and heavy venv
 ┣ 📜 requirements.txt       # Unified dependency list
 ┗ 📜 README.md              # Project Documentation
 
Created with ❤️ by @aliza-dev</div>
