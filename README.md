# 🤖 DevBot

> A focused, coding-only AI chatbot built with Python, Flask, and the OpenRouter API — designed to answer programming questions and nothing else.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-black?logo=flask&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-AI%20API-purple)
![HTML](https://img.shields.io/badge/Frontend-HTML%2FCSS%2FJS-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

DevBot is a minimal AI chatbot that stays strictly on-topic — coding only. It uses free AI models via the OpenRouter API to answer programming questions across languages and frameworks. The UI is a clean, responsive web interface built with HTML/CSS/JS and served through Flask.

---

## ✨ Features

- 💬 **Coding-only AI** — refuses off-topic queries, stays focused on programming
- ⚡ **Streaming responses** — token-by-token output for a live typing effect
- 🌐 **Web interface** — clean chat UI accessible from any browser
- 🆓 **Free AI models** — powered by OpenRouter's free-tier models (zero API cost)
- 🐍 **Flask backend** — lightweight Python server with minimal dependencies

---

## 🗂️ Project Structure

```
DevBot/
│
├── app.py            # Flask backend — routes, OpenRouter API calls, streaming
├── templates/
│   └── index.html    # Chat UI — HTML/CSS/JS frontend
├── .gitignore
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install flask requests python-dotenv
```

### Setup

1. Get a **free API key** from [openrouter.ai/keys](https://openrouter.ai/keys)

2. Create a `.env` file in the project root:
```
OPENROUTER_API_KEY=sk-or-v1-your-key-here
```

3. Run the app:
```bash
python app.py
```

4. Open your browser at: `http://127.0.0.1:5000`

---

## 🧰 Tech Stack

| Tech | Role |
|---|---|
| Python + Flask | Backend web server and API routing |
| OpenRouter API | Gateway to free AI language models |
| HTML / CSS / JS | Chat frontend interface |
| python-dotenv | Loads API keys from `.env` securely |

---

## 🔑 Environment Variables

| Variable | Required | Description |
|---|---|---|
| `OPENROUTER_API_KEY` | ✅ Yes | Your OpenRouter API key |
| `SECRET_KEY` | Optional | Flask session secret key |

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

> Built with ⚡ by [Dharanidharan M](https://github.com/dharani25007-code)
