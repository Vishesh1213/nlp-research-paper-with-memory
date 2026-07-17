# 🧠 AI Research Paper Intelligent System with Memory-Enabled Agent

An intelligent NLP-powered research assistant that helps users discover relevant research papers using semantic search, generates concise summaries, extracts keywords, and utilizes an AI agent with long-term memory for personalized interactions.

## 🚀 Features

- 📄 Research paper semantic search using Sentence Transformers
- 🔍 Fast similarity search with FAISS
- 📝 Automatic research paper summarization
- 🏷️ Keyword extraction using KeyBERT
- 🤖 Agentic AI powered by LangChain
- 🧠 Long-term memory for personalized conversations
- 💬 Natural language interface for querying research papers

---

## 🏗️ Project Pipeline

1. Data Collection
2. Text Extraction & Preprocessing
3. Embedding Generation (Sentence Transformers)
4. Vector Database Creation (FAISS)
5. Semantic Search
6. Summarization
7. Keyword Extraction
8. Agentic AI using LangChain
9. Long-Term Memory Integration

---

## 🛠️ Tech Stack

### Machine Learning & NLP
- Sentence Transformers
- Hugging Face Transformers
- KeyBERT

### Vector Database
- FAISS

### AI Agent Framework
- LangChain
- Groq LLM

### Data Processing
- Pandas
- NumPy
- Hugging Face Datasets

### Utilities
- Pickle
- UUID
- Tenacity

---

## 📂 Project Structure

```
.
├── nlp_Research_Paper_Intelligent_System_with_Memory.ipynb
├── README.md
└── requirements.txt (recommended)
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/your-repository.git
cd your-repository
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install pandas numpy faiss-cpu sentence-transformers transformers keybert datasets langchain langchain-groq groq tenacity
```

---

## ▶️ Usage

Open the notebook:

```bash
jupyter notebook
```

Run each notebook cell sequentially to:

- Load the research paper dataset
- Generate embeddings
- Build the FAISS index
- Perform semantic search
- Generate summaries
- Extract keywords
- Query the AI research assistant
- Store and recall user memories

---

## 🧠 How It Works

### 1. Semantic Search

User queries are converted into dense vector embeddings using Sentence Transformers. FAISS retrieves the most semantically similar research papers instead of relying on keyword matching.

### 2. Summarization

Retrieved papers are summarized using Hugging Face Transformer models, making it easier to understand key contributions.

### 3. Keyword Extraction

KeyBERT identifies important keywords from research papers to improve interpretability.

### 4. Memory-Enabled AI Agent

The LangChain agent can:

- Search research papers
- Summarize findings
- Extract keywords
- Save important user information
- Recall previous conversations using long-term memory

---

## 📌 Example Query

```
Find recent papers about reinforcement learning for robotics.
```

The system returns:

- Most relevant papers
- Similarity scores
- Paper summaries
- Important keywords

---

## 📚 Libraries Used

- sentence-transformers
- transformers
- faiss
- keybert
- datasets
- pandas
- numpy
- langchain
- langchain-groq
- groq
- tenacity

---

## 🎯 Future Improvements

- Web-based interface (Streamlit/Gradio)
- PDF upload support
- Citation generation
- Multi-document question answering
- Research paper recommendation system
- Persistent vector database (ChromaDB/Pinecone)
- Conversation history visualization

---

## 👨‍💻 Author

**Vishesh Raijada**

---

## 📄 License

This project is intended for educational and research purposes.
