# 💬 FIRST LLM - GPT-3.5 Turbo Chatbot

## 📌 Overview
The **FIRST LLM GPT-3.5 Turbo Chatbot** is a general-purpose conversational AI built with **FastAPI** and **React**.  
It connects to OpenAI's GPT-3.5 Turbo model to provide interactive, context-aware chat responses in a modern, responsive UI.

---

## 🛠 Tech Stack

**Frontend**  
- React (TypeScript)  
- Tailwind CSS  
- Axios  

**Backend**  
- Python  
- FastAPI  
- OpenAI GPT-3.5 Turbo API  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/DHILIP1808/FIRST-LLM--GPT-3.5-TURBO-Chatbot.git
cd FIRST-LLM--GPT-3.5-TURBO-Chatbot
```

### 2️⃣ Backend Setup
```bash
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```
- Create a `.env` file inside `backend`:
```env
OPENAI_API_KEY=your_api_key_here
```

### 3️⃣ Frontend Setup
```bash
cd frontend
npm install
```

---

## ▶️ Running the Project

### Start Backend
```bash
cd backend
uvicorn main:app --reload
```

### Start Frontend
```bash
cd frontend
npm run dev
```

Frontend: **http://localhost:5173**  
Backend: **http://127.0.0.1:8000**

---

## 📂 Folder Structure
```
FIRST-LLM--GPT-3.5-TURBO-Chatbot/
│
├── backend/
│   ├── main.py
│   ├── llm_service.py
│   ├── requirements.txt
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── tailwind.config.js
│
└── README.md
```

---

## 🌟 Features
- 🧠 General-purpose AI chat using GPT-3.5 Turbo  
- ⚡ FastAPI backend with RESTful API endpoints  
- 🎨 Responsive UI with Tailwind CSS  
- 🔑 Secure API key handling with `.env` file  

---

## 🚀 Future Improvements
- 💾 Add chat history  
- 🌐 Enable multilingual support  
- 📱 Mobile-optimized design  
