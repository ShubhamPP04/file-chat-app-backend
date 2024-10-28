# PDF Chat Application

A chat application that allows users to interact with PDF documents using Langchain and FastAPI for the backend, and React.js with Gemini Pro for the frontend.

## Features

- PDF document upload and processing
- Interactive chat interface with PDF content
- Powered by Google's Gemini Pro AI model
- Real-time conversation history
- Responsive web interface

## Architecture

### Backend
- FastAPI framework for REST API
- Langchain for document processing and chat functionality
- FAISS for vector storage and similarity search
- Google Generative AI (Gemini Pro) for text generation
- PyMuPDF for PDF processing

### Frontend
- React.js with Vite
- Tailwind CSS for styling
- Modern responsive design
- Real-time chat interface

## Setup Instructions

### Backend Setup

1. Clone the repository
2. Navigate to the backend directory
3. Install dependencies: `pip install -r requirements.txt`
4. Start the FastAPI server: `uvicorn main:app --reload`

