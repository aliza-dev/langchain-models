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
 
🛠️ Tech StackTechnologyPurposeLangChainOrchestration framework for LLMsOpenAIState-of-the-art Embeddings & Chat ModelsHugging FaceLocal open-source model integrationScikit-learnMathematical Cosine Similarity calculationsNumPyHigh-performance array manipulationsPython DotenvSecure environment variable management⚙️ Setup & Installation1. Clone the Repositorygit clone [https://github.com/aliza-dev/langchain-models.git](https://github.com/aliza-dev/langchain-models.git)
cd langchain-models
2. Virtual Environment Setup# Create and activate environment
python -m venv venv
# Windows
.\venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
3. Install Dependenciespip install -r requirements.txt
4. Configure SecretsCreate a .env file in the root directory:OPENAI_API_KEY="your_secret_key_here"
HUGGINGFACEHUB_API_TOKEN="your_hf_token_here"
💻 Running the ApplicationTo run the Document Similarity search engine (Identifying Indian Cricketers via semantic logic):python 3.EmbeddedModels/4_document_similarity.py
[!TIP]VS Code Interpreter Issue: If imports show errors, press Ctrl+Shift+P, type "Python: Select Interpreter", and choose the one inside your ./venv folder.🤝 ContributingContributions make the open-source community an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.Fork the ProjectCreate your Feature Branch (git checkout -b feature/NewModel)Commit your Changes (git commit -m 'Add some NewModel')Push to the Branch (git push origin feature/NewModel)Open a Pull Request<div align="center">Created with ❤️ by @aliza-dev</div>
