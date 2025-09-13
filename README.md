# 🌟 Lumo — AI Chatbot with Gemini Pro & OpenAI

Lumo is a lightweight, phase-wise learning project to explore **API usage**, **chatbot development**, and **AI integration**.  
It starts simple (build first), then gradually improves with security, speed, and advanced features.  

---

## 🚀 Features (Phase-Wise)

### ✅ Phase 1 — Core Learning
- Simple React frontend with chat UI
- Direct connection to **Gemini Pro API**
- Basic message/response display

### 🔒 Phase 2 — Protection
- Secure **backend (Node.js/Express or FastAPI)**
- API keys stored in `.env` (not exposed to frontend)
- Safe communication between frontend ↔ backend ↔ AI API

### ⚡ Phase 3 — User Experience
- Typing indicators while waiting
- Basic conversation history (in-session memory)
- Simple caching for repeated queries

### 📈 Phase 4 — Optimization
- Redis/file caching for faster responses
- Request batching (fewer API calls)
- Error handling + rate limiting

### 🌐 Phase 5 — Advanced
- Switch between **Gemini Pro** and **OpenAI**
- Persistent memory across sessions
- External API integrations (calendar, weather, etc.)
- Deployed on cloud (Vercel/Render/Heroku)

---

## 🛠️ Tech Stack
- **Frontend:** React + Vite + TailwindCSS  
- **Backend:** Node.js + Express (or FastAPI in Python)  
- **APIs:** Gemini Pro (default), OpenAI (optional)  
- **Styling:** TailwindCSS + ShadCN (for modern UI)  

---

## ⚙️ Setup & Installation

### 1️⃣ Clone the repo
```bash
git clone https://github.com/DebuggedMind/Lumo.git
cd lumo
