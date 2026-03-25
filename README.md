##SmartContext AI – LLM-Driven RAG Engine

This project implements a Retrieval-Augmented Generation (RAG) system using Google’s Gemini LLMs. It allows users to upload documents (.txt, .md, .pdf, .docx) and ask questions strictly grounded in the uploaded content. The model generates responses based only on the provided context, ensuring accurate and document-specific answers.

Live on Streamlit Cloud:
https://gemini-ragsystem-llm.streamlit.app/

Key Features

Multi-format document support: Parses text, Markdown, PDF, and Word documents.

LLM-powered Q&A: Uses the Google Gemini API to generate context-aware responses.

Interactive Streamlit UI: Simple interface for uploading documents, viewing extracted text, and asking questions.

Robust error handling: Displays clear messages for unsupported files or API failures.

Session state management: Maintains uploaded content and chat history for a smooth user experience.

This project showcases a practical implementation of RAG systems with large language models and can be extended to build knowledge assistants, document-based chatbots, and research tools.

Tech Stack

Python

Streamlit (frontend interface)

Google Gemini API (LLM backend)

pypdf (PDF text extraction)

python-docx (DOCX extraction)

python-dotenv (environment variable management)
