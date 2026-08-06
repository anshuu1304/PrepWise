# AI Technology Stack

This document describes the AI technologies used in PrepWise and the reason behind choosing each of them.

---

# Large Language Model (LLM)

**Model**
- Llama 3.1 8B

**Runtime**
- Ollama

**Purpose**
- Resume Parsing
- ATS Suggestions
- Resume Improvement
- Job Description Analysis
- Interview Question Generation
- Answer Evaluation
- Feedback Generation
- AI Career Coach

**Why we chose it**
- Free and open-source
- Can run locally
- High-quality responses
- Easy to replace with GPT or Claude later
- No API cost during development

---

# Speech-to-Text

**Model**
- Faster-Whisper

**Purpose**
- Convert interview audio into text before evaluation.

**Why we chose it**
- Fast inference
- High transcription accuracy
- Lightweight compared to Whisper
- Works locally
- Production ready

---

# Embedding Model

**Model**
- BAAI/bge-small-en-v1.5

**Purpose**
- Convert resumes, job descriptions, and interview knowledge into vector embeddings for semantic search.

**Why we chose it**
- Better semantic retrieval than MiniLM
- Lightweight
- Fast
- Excellent for RAG applications

---

# Vector Database

**Technology**
- FAISS

**Purpose**
- Store embeddings and retrieve the most relevant information during AI inference.

**Why we chose it**
- Industry standard
- Extremely fast similarity search
- Lightweight
- Perfect for local development

---

# AI Framework

**Framework**
- LangChain

**Purpose**
- Connect LLMs, prompts, embeddings, vector database, and retrieval pipelines.

**Why we chose it**
- Simplifies RAG development
- Large ecosystem
- Industry adoption
- Easy integration with Ollama and FAISS

---

# Resume Parsing

**Libraries**
- PyMuPDF
- python-docx
- spaCy
- Regex

**Purpose**
- Extract structured information from resumes.

**Why we chose them**
- PyMuPDF extracts text from PDFs efficiently.
- python-docx supports Word resumes.
- spaCy helps identify entities and linguistic patterns.
- Regex is effective for extracting emails, phone numbers, and other structured fields.

---

# Backend

- FastAPI
- PostgreSQL
- Redis

---

# Frontend

- Next.js
- React
- Tailwind CSS

---

# Deployment

- Docker
- GitHub Actions
- Nginx
- Ubuntu VPS

---

# Future Improvements

- DeepEval (LLM Evaluation)
- Reranking Models
- Hybrid Retrieval
- Confidence-aware RAG
- Fine-tuned LLMs

- ## Status

- [x] Technology Selected
- [ ] Implemented
- [ ] Tested
- [ ] Production Ready
