<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f1117,50:4ecdc4,100:0f1117&height=200&section=header&text=DevBot&fontSize=55&fontColor=ffffff&fontAlignY=40&desc=Coding-Only%20AI%20Chatbot%20%7C%20Flask%20%2B%20OpenRouter&descAlignY=60&descSize=18&animation=fadeIn"/>
</div>

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-7C3AED?style=for-the-badge)


> 🤖 A focused, coding-only AI chatbot — it answers programming questions and **nothing else.**

</div>

---

## 📌 Overview

DevBot is a minimal AI chatbot that stays strictly on-topic — **coding only**. Powered by free AI models via the OpenRouter API, it delivers fast, streamed answers to programming questions across all languages and frameworks through a clean web interface.

---

## ✨ Features

- 💬 **Coding-only AI** — refuses off-topic queries, stays focused
- ⚡ **Streaming responses** — token-by-token live typing effect
- 🌐 **Clean web UI** — responsive chat interface in any browser
- 🆓 **Free AI models** — zero API cost via OpenRouter free tier
- 🐍 **Lightweight Flask backend** — minimal dependencies

---

## 🗂️ Project Structure

```
DevBot/
├── app.py            # Flask backend — routes, OpenRouter API, streaming
├── templates/
│   └── index.html    # Chat UI
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Install
```bash
git clone https://github.com/dharani25007-code/DevBot.git
cd DevBot
pip install flask requests python-dotenv
```

### Configure
```bash
# Create .env
OPENROUTER_API_KEY=sk-or-v1-your-key-here
```
Get a free key at [openrouter.ai/keys](https://openrouter.ai/keys)

### Run
```bash
python app.py
```
Open: `http://127.0.0.1:5000`

---

## 🧰 Tech Stack

| Tech | Role |
|---|---|
| Python + Flask | Backend server and API routing |
| OpenRouter API | Free AI language models |
| HTML / CSS / JS | Chat frontend |
| python-dotenv | Secure API key loading |



<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:4ecdc4,100:0f1117&height=120&section=footer"/>

**Built by [Dharanidharan M](https://github.com/dharani25007-code) 
</div>
