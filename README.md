# AI Engineering Arsenal
## Your Hands-On Learning Journey

### 📁 Project Structure

```
ai-engineering-arsenal/
├── .env.example                    # Environment variables template
├── .gitignore                      # Git ignore patterns
├── requirements.txt                # All dependencies
├── README.md                       # This file
│
├── common/                         # Shared utilities
│   ├── __init__.py
│   ├── llm_clients.py             # Anthropic & OpenAI clients
│   ├── embeddings.py              # Embedding utilities
│   ├── vector_store.py            # Vector DB wrappers
│   └── utils.py                   # Helper functions
│
├── project-1-knowledge-base/       # Personal Knowledge Base
│   ├── README.md                  # Project-specific docs
│   ├── data/                      # Your PDFs/documents
│   ├── notebooks/                 # Jupyter experiments
│   ├── src/
│   │   ├── ingest.py             # Document processing
│   │   ├── query.py              # RAG query engine
│   │   └── app.py                # Streamlit UI
│   └── tests/                    # Unit tests
│
├── project-2-code-assistant/      # Code Documentation Assistant
│   ├── README.md
│   ├── repos/                    # Clone repos here
│   ├── notebooks/
│   ├── src/
│   │   ├── repo_indexer.py      # Code parsing & indexing
│   │   ├── semantic_search.py   # Search implementation
│   │   └── app.py               # Query interface
│   └── tests/
│
├── project-3-research-assistant/  # Automated Research Assistant
│   ├── README.md
│   ├── outputs/                  # Generated reports
│   ├── notebooks/
│   ├── src/
│   │   ├── search_agent.py      # MCP-powered search
│   │   ├── synthesizer.py       # Multi-source synthesis
│   │   └── app.py               # Main interface
│   └── tests/
│
└── learning/                      # Learning resources
    ├── youtube-playlist.md        # Curated video list
    ├── code-snippets/            # Useful patterns
    └── notes/                    # Your learning notes
```

### 🚀 Quick Start

#### 1. Environment Setup
```bash
# Create virtual environment
python -m venv venv

# Activate (macOS/Linux)
source venv/bin/activate

# Activate (Windows)
venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

#### 2. Configure API Keys
```bash
# Copy example env file
cp .env.example .env

# Edit .env and add your keys:
# - ANTHROPIC_API_KEY
# - OPENAI_API_KEY (for embeddings)
```

#### 3. Choose Your Starting Project
Each project has its own README with detailed setup instructions.

**Recommended order:**
1. Start with **Project 1** (Knowledge Base) - Learn RAG fundamentals
2. Move to **Project 2** (Code Assistant) - Understand code embeddings
3. Finish with **Project 3** (Research) - Master MCP & agents

### 📚 Learning Path

Follow the curated YouTube playlist in `learning/youtube-playlist.md`

**Week 1-2:** Foundation videos + Project 1
**Week 3-4:** RAG deep dives + Project 2  
**Week 5-6:** Advanced concepts + Project 3
**Week 7-8:** Production & deployment

### 🎯 Goals

By completing all three projects, you'll have:
- ✅ Built 3 production-ready AI applications
- ✅ Mastered RAG architecture patterns
- ✅ Understood embeddings & vector databases
- ✅ Implemented MCP for tool integration
- ✅ Gained hands-on experience with LLM APIs
- ✅ Created a portfolio to showcase

### 🛠️ Tech Stack Summary

**LLMs:** Claude (Anthropic), GPT-4 (OpenAI)
**Frameworks:** LangChain, LlamaIndex
**Vector DBs:** ChromaDB, Qdrant, Pinecone
**Document Processing:** pypdf, python-docx, unstructured
**Code Analysis:** tree-sitter, pygments, GitPython
**Observability:** LangSmith, RAGAS
**Deployment:** FastAPI, Streamlit, Gradio

### 💡 Tips

1. **Start small** - Get one project working before moving on
2. **Iterate** - Don't aim for perfection on first try
3. **Experiment** - Try different prompts, chunk sizes, models
4. **Document** - Keep notes in `learning/notes/`
5. **Build in public** - Share your progress on GitHub

### 🤝 Next Steps

1. Run `python -m pytest` to verify setup
2. Start with Project 1 - see `project-1-knowledge-base/README.md`
3. Join AI communities (Discord, Reddit) for support
4. Share what you build!

---

**Happy Building! 🚀**
