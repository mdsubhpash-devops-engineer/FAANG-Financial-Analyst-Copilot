# 🚀 GenAI Financial Analyst & Stock Research Copilot

An advanced Retrieval-Augmented Generation (RAG) and Agentic workflow system designed to automate financial data extraction, vector indexing, and intelligent stock research analysis.

## 🛠️ Tech Stack & Architecture
* **Core Language:** Python
* **Financial Data Provider:** Yahoo Finance (`yfinance`) API
* **Vector Database:** FAISS (Facebook AI Similarity Search)
* **Embeddings & NLP:** Sentence-Transformers (`all-MiniLM-L6-v2`)
* **Frameworks:** LangChain, HuggingFace, PyTorch

## ✨ Key Features
1. **Live Financial Data Scraping:** Automatically fetches real-time stock quotes, market capitalization, sector classification, and business summaries.
2. **Semantic Text Chunking & RAG:** Splits extensive financial disclosures into optimized chunks and indexes them using vector embeddings.
3. **FAISS Vector Search:** Enables millisecond-level retrieval of relevant financial context based on user queries.
4. **AI Analyst Copilot:** Generates structured financial research reports, risk assessments, and investment watchlist recommendations.

## 📊 Execution Flow
* Extracts live ticker information via API.
* Generates vector embeddings for semantic indexing.
* Executes similarity search and compiles automated analyst insights.
