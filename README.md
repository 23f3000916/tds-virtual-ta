# TDS Virtual TA – IITM Online DS

This is a Virtual Teaching Assistant for the Tools for Data Science (TDS) course. It uses a RAG (Retrieval-Augmented Generation) pipeline to answer student queries based on course content and Discourse posts.

## 🚀 Features

- Query answering via FastAPI
- Uses OpenAI embeddings and GPT via AIPipe
- Returns answers with relevant links
- Swagger UI available at `/docs`

## ⚙️ How to Run

1. Install dependencies:
   pip install -r requirements.txt

2. Create a .env file in the project root:
   API_KEY=Bearer your_api_key_here

3. Start the server:
   uvicorn app:app --reload --port 8000

4. Open Swagger UI at:
   http://localhost:8000/docs

📤 Endpoints
POST /api/ – Query the virtual TA

POST / – Returns a placeholder (required for assignment submission)

Built for the IITM Online BSc Data Science TDS project.
