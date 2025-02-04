🏨 Multi-Language Hotel Search Engine
📌 Overview
The Multi-Language Hotel Search Engine is an AI-powered search system designed to help users find hotels efficiently. It supports multiple languages, leveraging BM25, FAISS, and embeddings-based retrieval for optimal search results.

🔥 Features
🔍 Hybrid Search: Combines BM25 (text-based) and FAISS (vector-based) for enhanced ranking.
🌍 Multi-Language Support: Enables searches in different languages.
⚡ Fast & Scalable: Optimized retrieval using embedding models and re-ranking techniques.
📊 Interactive UI: Gradio-based interface for user-friendly hotel exploration.
🛠️ Tech Stack
Backend: FastAPI, Flask
Search & Ranking: FAISS, BM25, Meilisearch
Machine Learning: Sentence Transformers, Jina AI Reranker
Containerization: Docker
Deployment: Cloud-compatible
🚀 Setup & Installation
1️⃣ Clone the repository:

bash
Copy
Edit
git clone https://github.com/Hatim-0101/multi_lang_hotel_search_eng.git
cd multi_lang_hotel_search_eng
2️⃣ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
3️⃣ Run the application:

bash
Copy
Edit
python app.py
📂 Notebook
For detailed processing, check the Jupyter Notebook:
📜 Multi_Lang_Hotel_search_engine.ipynb

🤝 Contributing
Feel free to fork, improve, and submit a PR! Contributions are welcome.

📜 License
MIT License
