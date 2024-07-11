# DocTalker

DocTalker is a document-upload-and-chat application powered by GPT, Embedding, LangChain, and Supabase. It allows users to upload documents, extract and store their content, create embeddings, and interact with the content through a chat interface using Streamlit.

## Features

- **Upload Documents**: Supports uploading of text, PDF, and Word documents.
- **Extract Text**: Automatically extracts text from uploaded documents.
- **Store Content**: Saves document content and embeddings in Supabase.
- **Generate Embeddings**: Uses LangChain to generate embeddings for the extracted content.
- **Chat with Documents**: Leverages GPT to enable interactive chat with the document content.

## Project Structure

```plaintext
doctalker/
├── app.py
├── requirements.txt
├── .env
└── README.md
