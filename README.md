# Student Counselor Chat Application

A web-based AI-powered chatbot designed to provide concise and empathetic support for students facing academic, personal, or emotional challenges.

---

## Features

- AI-powered chat using Google Gemini API  
- Focused on student mental health and academic support  
- Flask-based backend API (`/api/chat`)  
- Responsive frontend interface  
- Debug UI for inspecting API requests and responses  
- Safety-aware responses with controlled filtering  

---

## Project Structure
project/
│── app.py # Flask backend server
│── index.html # Main chat UI
│── chat2.html # Debug UI
│── requirements.txt # Dependencies
│── knowledge_base2.json # Sample responses
│── .env # Environment variables (not included)


---

## Installation

### 1. Clone the repository


### 2. Install dependencies


### 3. Set up environment variables

Create a `.env` file in the root directory:


---

## Running the Application



The server will start at:
http://localhost:8000


---

## Frontend Interfaces

### Main Chat UI
- File: `index.html`  
- Provides a clean interface for student interaction  

### Debug UI
- File: `chat2.html`  
- Displays:
  - Request JSON  
  - Response JSON  
  - Headers  
  - Errors  

---

## API Endpoint

### POST `/api/chat`

#### Request
```json
{
  "message": "I feel stressed about exams"
}
Response
{
  "reply": "It's normal to feel stressed..."
}
