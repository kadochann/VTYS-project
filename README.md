# AI-Powered Production Data Management System – Ford Otosan  
**DBMS 2024-2025 Term Project**

This project was developed to improve Ford Otosan Eskişehir's production data management workflow. The existing system suffered from unstructured and inconsistent data, which limited the performance of their internal chatbot.

## 🧠 Project Highlights
- **Vector Database Integration**  
  Migrated production data into a vector database (ChromaDB) for efficient semantic search.

- **Data Cleaning & Structuring**  
  Removed duplicates, standardized inconsistent records, and categorized raw data using Python tools like `pandas` and `regex`.

- **Semantic Search**  
  Implemented cosine similarity using sentence embeddings to enable meaning-based queries.

- **Chatbot Integration**  
  Developed an intelligent chatbot using Gemini LLM that responds contextually based on the vectorized data.

- **Authentication**  
  Google OAuth is used for secure user login.

> ⚠️ **Note on Authentication**  
Authentication credentials (e.g., API keys, client secrets) are stored in a local `.env` file, which is ignored via `.gitignore` for security.  
To run this application locally:
1. Obtain new authentication credentials (e.g., access token or client secrets).
2. Assign them to the corresponding variables in `chatbot.py`.

## 🔧 Technologies Used
- **Python**  
- **ChromaDB** (Vector Database)  
- **Gemini API** (LLM integration)  
- **SentenceTransformers** (Text embeddings)  
- **Pandas**, **Regex** (Data preprocessing)  
- **Tkinter** (Desktop GUI)

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/ford-otosan-vector-db.git
cd ford-otosan-vector-db

# Install dependencies
pip install -r requirements.txt

# Add your credentials to the .env file
touch .env
# Then manually add:
# GOOGLE_CLIENT_ID=your_id
# GOOGLE_CLIENT_SECRET=your_secret
# GEMINI_API_KEY=your_key

# Run the chatbot application
python chatbot.py
```
📅 Last Updated
February 1st, 2025 – Kadriye Harmancı
