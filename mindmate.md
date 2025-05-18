# 🧠 MindMate – Your AI-Powered Virtual Companion

MindMate is a revolutionary virtual companion powered by AI that talks like a human, adapts to your mood, tells jokes, helps solve problems, and suggests personalized roadmaps for growth — be it emotional, mental, physical, or financial.

---

## 🌟 Key Features

- 🎙️ **Conversational Agent**: Natural interaction with a male/female voice interface
- 😂 **Mood-based Humor**: Cracks jokes depending on your mood
- 🧠 **Emotion Detection**: Remembers your emotional, financial, and physical state
- 🗺️ **Personal Roadmaps**: Personalized plans to solve user problems (e.g. financial freedom, mental wellness)
- 🧾 **Memory**: Remembers past conversations and feelings
- 🎯 **Goal Tracking**: Offers guidance and checks in on your progress

---

## 🚀 Tech Stack

| Layer      | Stack                            |
|------------|----------------------------------|
| **Frontend** | React, Tailwind CSS              |
| **Backend**  | FastAPI, OpenAI (GPT-4), Python  |
| **API**      | REST via FastAPI                |
| **IDE**      | Cursor AI (recommended)         |
| **Tools**    | Git, VS Code/IntelliJ/Cursor    |

---

## 🏗️ Project Structure & Directory Paths

```

mindmate/                        ← Root directory
│
├── backend/                     ← FastAPI + AI Engine (Python)
│   ├── main.py                  ← FastAPI entry point
│   ├── models.py                ← Pydantic models (future use)
│   ├── routes/
│   │   └── chatbot.py           ← /chat endpoint logic
│   ├── services/
│   │   └── ai\_engine.py         ← GPT-4 integration + AI logic
│   └── requirements.txt         ← Python dependencies
│
├── frontend/                    ← React Frontend
│   ├── public/                  ← Static files (favicon, etc.)
│   ├── src/
│   │   ├── components/
│   │   │   └── ChatBot.jsx      ← Main Chat UI
│   │   ├── App.jsx              ← App wrapper
│   │   └── main.jsx             ← React entry point
│   ├── tailwind.config.js       ← TailwindCSS config
│   └── package.json             ← React dependencies
│
├── .gitignore                   ← Git ignored files
└── README.md                    ← This file

````

---

## ⚙️ Setup Instructions

### ✅ Prerequisites

- Node.js >= 18
- Python >= 3.10
- OpenAI API Key
- Git

---

### 🔧 Backend Setup

```bash
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt

# Start server
uvicorn main:app --reload
````

🔑 **Set your OpenAI API Key**
In `backend/services/ai_engine.py`, replace:

```python
openai.api_key = "your-openai-key"
```

with your real key or store it securely using `dotenv`.

---

### 🎨 Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

🌐 Visit your app at: `http://localhost:5173`
📡 Make sure your backend is running at: `http://localhost:8000`

---

## 📡 API Reference

### POST `/chat`

#### Request

```json
{
  "message": "I'm feeling anxious and broke."
}
```

#### Response

```json
{
  "reply": "I'm here for you 💙. Let's talk about how to reduce stress and start building financial independence..."
}
```

---

## 🧠 Upcoming Features

* [ ] Persistent user state (memory)
* [ ] Mood prediction using NLP sentiment analysis
* [ ] Dynamic voice output (text-to-speech)
* [ ] Admin dashboard for user stats
* [ ] Roadmap generator (career, health, finance)
* [ ] Notification system for daily mental check-ins

---

## 🌍 Deployment (Coming Soon)

* 🔐 Backend: Railway / Render / Fly.io
* 🌐 Frontend: Vercel / Netlify
* 🧪 Env secrets stored via `.env` files

---

## 🤝 Contribution Guide

1. Clone the repo

   ```bash
   git clone https://github.com/your-username/mindmate.git
   ```
2. Create a branch:

   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit and push

   ```bash
   git commit -m "Add feature"
   git push origin feature/your-feature-name
   ```

Pull Requests are welcome! 🚀

---

## 👨‍💻 Built & Maintained By

**Abhishek Tomar**
💼 [LinkedIn](https://www.linkedin.com/in/abhishek-tomar-7aa29127b)
💻 [GitHub](https://github.com/Abhishek-09-Tomar)
📹 [YouTube](https://www.youtube.com/@i_am_abhishek_tomar)

---

## 📜 License

This project is under the MIT License — feel free to use and extend.

---

## 💌 Final Words

> “The mind is not a vessel to be filled but a fire to be kindled.”
> Let MindMate be that spark for millions. 🔥

```

---

Let me know if you want this `README.md` exported as a file or auto-uploaded to your GitHub repo.
```
