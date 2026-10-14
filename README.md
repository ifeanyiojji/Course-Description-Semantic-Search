# Course Description Semantic Search

A semantic search application that allows users to find and explore academic courses using natural language queries, powered by vector embeddings and **Pinecone**.

## 🚀 Features
- **Semantic Course Retrieval:** Find relevant courses even if your search terms don't match the exact words in the course catalog.
- **Pinecone Vector Database:** Fast, scalable similarity search for high-dimensional course embeddings.
- **Weighted Assignment Integration:** Custom pipeline supporting weighted logic for course matching.
- **Natural Language Understanding:** Search using everyday descriptions (e.g., *"an introductory class about machine learning and python"*).

---

## 🛠️ Tech Stack
- **Python**
- **Jupyter Notebook**
- **Vector Database:** [Pinecone](https://www.pinecone.io/)
- **Data Processing:** Pandas, NumPy

---

## 📁 Project Structure
```text
Course-Description-Semantic-Search/
│
├── course_descriptions.csv                  # Raw/processed course catalog dataset
├── course_section_descriptions.csv          # Detailed course section dataset
├── Vectore Store.ipynb                      # Notebook for vector store setup & configuration
├── Vector Store Index.ipynb                 # Notebook for indexing vectors into Pinecone
├── Pinecone Semantic Search Course Description with weighted assignment.ipynb # Main workflow with weighted logic
└── README.md
