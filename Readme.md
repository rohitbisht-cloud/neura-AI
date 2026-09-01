# 🤖 NEURA AI

### AI-Powered Conversational Assistant

NEURA AI is a modern full-stack AI chat application designed to provide intelligent, fast and interactive conversations through a clean and responsive interface.

The application combines a React frontend, FastAPI backend, cloud database and AI inference service into a complete full-stack system.

---

## ✨ Features

### 💬 AI Chat

- Real-time AI responses
- Streaming responses
- Conversation history
- Multiple conversations
- Regenerate AI responses
- Delete conversations
- Archive conversations
- Context-aware conversations

### 📎 File Processing

- PDF file processing
- DOCX file processing
- TXT file processing
- Extract text from uploaded documents
- Use document content during conversations

### 🔐 Authentication

- User registration
- Secure login
- JWT authentication
- Password hashing
- Protected API routes
- Session management
- Password recovery system

### 👍 Feedback

- Rate AI responses
- Positive feedback
- Negative feedback
- Feedback statistics

### 🎨 User Interface

- Modern responsive design
- Dark and light themes
- Responsive sidebar
- Mobile-friendly interface
- Smooth interactions
- Toast notifications
- Markdown-supported AI responses

---

# 🛠️ Technology Stack

## Frontend

- React
- Vite
- Tailwind CSS
- Axios
- React Router
- React Markdown
- React Icons

## Backend

- Python
- FastAPI
- SQLAlchemy
- Async SQLAlchemy
- aiomysql
- JWT Authentication
- Password Hashing

## AI

- Groq API
- Configurable AI model
- Streaming AI responses

## Database

- TiDB Cloud
- MySQL-compatible database
- Asynchronous database connection

## Deployment

- Vercel — Frontend
- Render — Backend
- TiDB Cloud — Database

---

# 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │      NEURA AI       │
                    │   React + Vite      │
                    └──────────┬──────────┘
                               │
                               │ HTTPS
                               ▼
                    ┌─────────────────────┐
                    │      FastAPI        │
                    │      Backend        │
                    └───────┬─────┬───────┘
                            │     │
                 ┌──────────┘     └──────────┐
                 ▼                           ▼
        ┌─────────────────┐          ┌─────────────────┐
        │   TiDB Cloud    │          │     Groq AI     │
        │    Database     │          │  AI Inference   │
        └─────────────────┘          └─────────────────┘
neura-AI/
│
├── backend/
│   ├── main.py
│   ├── database.py
│   ├── models.py
│   ├── schemas.py
│   ├── auth.py
│   ├── ai_service.py
│   ├── file_processor.py
│   ├── email_service.py
│   ├── requirements.txt
│   └── .env.example
│
├── database/
│   └── schema.sql
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── contexts/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── assets/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── package.json
│   ├── vite.config.js
│   └── tailwind.config.js
│
├── .gitignore
├── render.yaml
└── README.md