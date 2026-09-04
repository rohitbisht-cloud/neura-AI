# 🤖 NEURA AI

### AI-Powered Conversational Assistant

NEURA AI is a modern full-stack AI chat application built to provide fast, intelligent and interactive conversations through a clean and responsive interface.

The application combines a React frontend, FastAPI backend, MySQL database and Groq AI inference into a complete full-stack conversational platform.

---

## 🚀 Live Demo

### 🌐 Frontend
> Add your Vercel deployment URL here

### ⚡ Backend API
https://neura-ai-1-28dr.onrender.com

### 📚 API Documentation
https://neura-ai-1-28dr.onrender.com/docs

---

## ✨ Features

### 💬 AI Chat

- AI-powered conversations
- Real-time responses
- Streaming AI responses
- Conversation history
- Multiple conversations
- Context-aware conversations
- Regenerate AI responses
- Delete conversations
- Archive conversations

### 📎 File Processing

- PDF document processing
- DOCX document processing
- TXT document processing
- Text extraction from uploaded documents
- Document-based conversations

### 🔐 Authentication

- User registration
- Secure login
- JWT authentication
- Password hashing
- Protected API routes
- Session management
- Password recovery
- OTP verification
- Password reset

### 👍 Feedback System

- Rate AI responses
- Positive feedback
- Negative feedback
- Feedback statistics

### 🎨 User Interface

- Modern responsive UI
- Dark and light themes
- Responsive sidebar
- Mobile-friendly design
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
- Streaming AI inference

## Database

- MySQL
- MySQL-compatible database
- Async database connection

## Deployment

- Vercel — Frontend
- Render — Backend
- MySQL — Database

---

# 🏗️ System Architecture

```text
                         ┌──────────────────────┐
                         │      NEURA AI        │
                         │   React + Vite       │
                         └──────────┬───────────┘
                                    │
                                    │ HTTP / HTTPS
                                    ▼
                         ┌──────────────────────┐
                         │       FastAPI        │
                         │       Backend        │
                         └───────┬───────┬──────┘
                                 │       │
                         ┌───────┘       └────────┐
                         ▼                        ▼
                ┌─────────────────┐       ┌─────────────────┐
                │     MySQL       │       │     Groq AI     │
                │    Database     │       │  AI Inference   │
                └─────────────────┘       └─────────────────┘
