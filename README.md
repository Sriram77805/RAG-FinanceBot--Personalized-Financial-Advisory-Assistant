# 💹 RAG-Based Personalized Financial Advisor Chatbot  

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)  
![License](https://img.shields.io/badge/License-MIT-green)  
![FAISS](https://img.shields.io/badge/FAISS-Semantic%20Search-orange)  
![ChromaDB](https://img.shields.io/badge/ChromaDB-Metadata%20Filtering-purple)  
![yFinance](https://img.shields.io/badge/yFinance-Real%20Time%20Stock%20Data-yellow)  

> 🚀 AI-powered chatbot that **blends LLM capabilities with real-time market data** to deliver **personalized stock recommendations** based on your risk appetite, ROI goals, and sector interests.  

---

## ✨ Features
✅ **🎯 Custom Investment Advice** – Tailored portfolio suggestions based on ROI, volatility, and market preferences.  
✅ **🔍 Context-Aware Retrieval** – FAISS-powered semantic search with ChromaDB metadata filtering.  
✅ **🤖 AI-Powered Explanations** – Google Gemini API generates human-like, insightful investment insights.  
✅ **📈 Live Market Data** – Real-time prices fetched via yFinance for actionable decisions.  

---

## 🛠️ Tech Stack
| Category             | Technology |
|----------------------|------------|
| Language             | Python |
| Vector Search        | FAISS |
| Metadata Filtering   | ChromaDB |
| LLM API              | Google Gemini |
| Market Data          | yFinance |
| Embeddings           | SentenceTransformers (MiniLM) |
| Orchestration        | LangChain |

---

## 🗂 Architecture Overview
```mermaid
flowchart TD
    A[User Input] --> B[ChromaDB Metadata Filtering]
    B --> C[FAISS Semantic Search (MiniLM Embeddings)]
    C --> D[Google Gemini API - Advice Generation]
    D --> E[yFinance API - Real-Time Market Data]
    E --> F[Final Recommendation Output]
```

---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Sriram77805/RAG-FinanceBot--Personalized-Financial-Advisory-Assistant.git
cd RAG-FinanceBot--Personalized-Financial-Advisory-Assistant
```

### 2️⃣ Install Dependencies
```bash
pip install faiss-cpu chromadb yfinance sentence-transformers google-generativeai ipython
```

### 3️⃣ Configure Gemini API
```python
import google.generativeai as genai
genai.configure(api_key="YOUR_API_KEY")
```

### 4️⃣ Run the Notebook
- Open in **Jupyter Notebook** or **Google Colab**  
- Load embeddings, enter preferences, and generate AI-driven investment suggestions.

---

## 📊 Example Output
**Top 5 Suggested Stocks:**
1. **AAPL** – Stable growth, ideal for balanced portfolios.  
2. **TSLA** – High growth potential for risk-tolerant investors.  
3. **MSFT** – Consistent performer in the tech sector.  
4. **NVDA** – Strong market momentum in AI and gaming.  
5. **JNJ** – Defensive healthcare option with steady dividends.  

---

