# 🚀 Enterprise AI Requirements-to-Code Assistant

## 📌 Overview
This project is an AI-powered semantic code assistant that converts natural language software requirements into relevant Python code snippets using embeddings and vector similarity search.

It simulates enterprise-grade developer tools used for intelligent code retrieval and internal coding assistants.

---

## ⚙️ Tech Stack
- Python
- Sentence Transformers (MiniLM)
- FAISS (Vector Search)
- Scikit-learn (TSNE / PCA)
- Matplotlib

---

## 🧠 How It Works
1. Natural language requirements are paired with code snippets
2. Text is converted into vector embeddings
3. FAISS indexes embeddings for fast similarity search
4. User query is embedded and matched against stored vectors
5. Top-ranked code snippets are returned with confidence scores

---

## 🚀 Features
- Natural language → code retrieval
- Semantic search using embeddings
- FAISS-based vector similarity engine
- Ranking system with confidence scores
- Embedding visualization (PCA / t-SNE)
- Lightweight and fully offline

---

## 📊 Visualizations
- Similarity score bar charts
- Embedding space clustering (t-SNE / PCA)
- Heatmap of top matches
- Confidence distribution plots

---

## 🧪 Example
**Input:**

**Output:**
```python
import pandas as pd
df = pd.read_csv('file.csv')
```
---
## ▶️ How to Run

Run the notebook step by step in Google Colab or Jupyter Notebook.

Install dependencies:

pip install sentence-transformers faiss-cpu scikit-learn matplotlib

---
## 📈 Future Improvements
1. Integrate GPT-based code generation
2. Add FastAPI backend for deployment
3. Build Streamlit chatbot UI
4. Support multi-language code retrieval
5. Deploy on AWS using Docker
