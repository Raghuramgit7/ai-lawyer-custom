# ⚖️ AI Lawyer - RAG with DeepSeek R1

An AI-powered legal chatbot that leverages Retrieval-Augmented Generation (RAG) with DeepSeek R1 and Ollama for advanced legal reasoning. This chatbot is designed to assist users in understanding complex legal documents, retrieving relevant case laws, and providing structured legal insights. By integrating DeepSeek R1, a sophisticated reasoning model, with the RAG framework, AI Lawyer ensures that responses are grounded in factual legal texts, reducing hallucinations and enhancing reliability. The chatbot can process large legal documents, break them down into meaningful sections, and retrieve the most pertinent information to answer user queries accurately.

## Features

- 📂 Upload and analyze legal documents (PDFs)
- 🔍 Retrieve relevant legal information using a FAISS vector database
- 🤖 Answer legal questions using DeepSeek R1 with Groq
- 📜 Summarize legal documents
- 📄 Generate downloadable AI-generated legal reports

## Project Structure

```
├── frontend.py          # Streamlit UI for AI Lawyer
├── rag_pipeline.py      # Retrieval-Augmented Generation pipeline
├── vector_database.py   # FAISS-based vector database
├── requirements.txt     # Python dependencies
└── README.md            # Project documentation
```

## Technologies Used

- **DeepSeek R1** – AI model for complex reasoning
- **Ollama** – Local LLM hosting
- **LangChain** – AI framework for LLM applications
- **Streamlit** – Frontend UI for chatbot
- **FAISS** – Vector search for document retrieval
- **pdfplumber** – PDF document processing

## Installation & Setup

1. Clone the repository:
   ```
   git clone <your-repo-url>.git
   cd <repo-name>
   ```

2. Set up a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows
   ```

3. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

Run the Streamlit application:

```
streamlit run frontend.py
```

1. Upload a legal document (PDF).
2. Ask legal questions and get AI-powered responses.
3. Download AI-generated legal reports.

## How It Works

1. **Upload PDF:** Documents are uploaded and processed.
2. **Vector Database:** FAISS indexes the document text.
3. **Query Handling:** The system retrieves relevant information.
4. **LLM Response:** DeepSeek R1 generates answers.
5. **Report Generation:** The system generates a downloadable PDF report.

## Contact

For questions or support, contact me at:

📧 raghuram0311@gmail.com

## Connect With Me

- 🐙 [GitHub](https://github.com/Raghuramgit7)
- 🔗 [LinkedIn](https://www.linkedin.com/in/raghuramgn/)
