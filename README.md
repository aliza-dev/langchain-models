<div align="center">🦜🔗 LangChain ModelsA deep dive into LangChain's Model I/O layer: Implementing LLMs, Chat Models, and Vector Embeddings.</div>📖 Overviewlangchain-models is a comprehensive collection of Python implementations focused on the "Model" component of the LangChain framework. This repository demonstrates how to bridge the gap between raw data and AI intelligence using state-of-the-art models from OpenAI and Hugging Face.Key Features⚡ LLM Integration: Direct interaction with large language models for text generation.💬 Chat Interfaces: Implementing structured conversations using System, Human, and AI message schemas.🔍 Semantic Search: Generating high-dimensional vector embeddings and calculating Cosine Similarity to find relevant context from custom datasets (e.g., Cricketer profiles).🗂️ Project StructureThe repository is organized following the LangChain Model I/O architecture:📦 langchain-models
 ┣ 📂 1.LLMs/                # Standard Large Language Model integrations
 ┣ 📂 2.ChatModels/          # Conversational Chat Model implementations
 ┣ 📂 3.EmbeddedModels/      # Vector Embeddings & Semantic Analysis
 ┃ ┣ 📜 1_embedding_openai_query.py
 ┃ ┣ 📜 2_embedding_openai_docs.py
 ┃ ┣ 📜 3_embedding_hf_local.py
 ┃ ┗ 📜 4_document_similarity.py    # Semantic search with Scikit-learn & NumPy
 ┣ 📜 .env                   # Configuration & API Keys (Private)
 ┣ 📜 .gitignore             # Security rules to prevent secret leaks
 ┣ 📜 requirements.txt       # Project dependencies
 ┗ 📜 README.md              # Project documentation
🚀 Getting StartedFollow these steps to set up the environment and run the scripts locally.1. PrerequisitesPython 3.8+ installed.OpenAI API Key (for OpenAI scripts).HuggingFace Access Token (for HF scripts).2. InstallationClone the repository and install the dependencies:# Clone the repository
git clone [https://github.com/aliza-dev/langchain-models.git](https://github.com/aliza-dev/langchain-models.git)
cd langchain-models

# Create a virtual environment
python -m venv venv

# Activate venv (Windows)
.\venv\Scripts\activate
# Activate venv (Mac/Linux)
source venv/bin/activate

# Install required packages
pip install -r requirements.txt
3. Environment ConfigurationCreate a .env file in the root directory and add your credentials:OPENAI_API_KEY="your-openai-api-key-here"
HUGGINGFACEHUB_API_TOKEN="your-hf-token-here"
💻 Usage ExampleTo execute the Document Similarity script (which identifies cricketers based on semantic similarity):python 3.EmbeddedModels/4_document_similarity.py
Note: If you see "Import could not be resolved" in VS Code, ensure you have selected the correct Python Interpreter by pressing Ctrl + Shift + P and choosing the venv environment.🛠️ Tech StackLangChain: Core framework.OpenAI: text-embedding-3-large & Chat models.HuggingFace: Open-source local embeddings.Scikit-learn: For Cosine Similarity calculations.Python Dotenv: For secure environment management.🤝 ContributingContributions are welcome! If you have more model examples or improvements, feel free to open a Pull Request.Created with ❤️ by @aliza-dev
