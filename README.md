# 📚 Knowledge Base & RAG Bot

A document-grounded chatbot built using Streamlit, LangChain, and Google Gemini. It answers questions using uploaded or built-in documents and provides source references.

## Features

- Ask questions about documents using natural language.
- Supports PDF, TXT, and Markdown files.
- Uses Google Gemini embeddings and Gemini Flash for answer generation.
- Splits documents into smaller chunks for retrieval.
- Displays source filenames and page numbers.
- Provides a fallback response when information is unavailable.
- Visitors provide their own Gemini API key, which is not saved.

## Tech Stack

- Python
- Streamlit
- LangChain
- Google Gemini API
- PyPDF

## Project Structure

```text
knowledge-base-rag-bot/
├── app.py
├── rag_core.py
├── requirements.txt
├── .gitignore
├── tests.md
└── knowledge_base/
    ├── AI_Basics.txt
    ├── Machine_Learning.txt
    └── RAG_Basics.txt
```

## Run Locally

1. Clone the repository.
2. Create and activate a virtual environment.
3. Install dependencies:

```bash
pip install -r requirements.txt
```

4. Start the application:

```bash
streamlit run app.py
```

5. Enter your Gemini API key in the sidebar.

Get a Gemini API key from https://aistudio.google.com/apikey.

## Testing

Six test cases covering basic facts, retrieval, unanswerable questions, and tricky questions are documented in `tests.md`.

## Privacy

The application uses the visitor-provided Gemini API key for API requests. The key is not intentionally saved to a file or committed to the repository.

Deployment link: https://ehb8if8w6w2fsnahwxobku.streamlit.app/

Repository Link: https://github.com/Achu-24/-knowledge-base-rag-bot