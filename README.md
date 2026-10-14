# Course Description Semantic Search

A semantic search application that allows users to find and explore academic courses using natural language queries, powered by vector embeddings and **Pinecone**.

## 🚀 Features
- **Semantic Course Retrieval:** Find relevant courses even if your search terms don't match the exact words in the course catalog.
- **Pinecone Vector Database:** Fast, scalable similarity search for high-dimensional course embeddings.
- **Natural Language Understanding:** Search using everyday descriptions (e.g., *"an introductory class about machine learning and python"*).

---

## 🛠️ Tech Stack
- **Python**
- **Vector Database:** [Pinecone](https://www.pinecone.io/)
- **Embeddings / NLP:** *(e.g., OpenAI, Hugging Face Sentence-Transformers)*
- **Backend / Interface:** *(e.g., FastAPI, Flask, or Streamlit)*

---

## 📁 Project Structure
```text
Course-Description-Semantic-Search/
│
├── data/               # Raw and processed course datasets
├── notebooks/          # Jupyter notebooks for data processing & experimentation
├── src/                # Source code (embedding generation, Pinecone setup, search logic)
├── requirements.txt    # Project dependencies
└── README.md
