# 💻 DevBot – Coding-Only AI Chatbot

DevBot is an AI-powered coding assistant built using **Python**, **Flask**, and **OpenRouter API**.  
It answers strictly programming and software development related questions.

---

## 🚀 Live Demo

(After deployment, add your website link here)

```
https://your-devbot-url.com
```

---

## ✨ Features

- 🤖 AI-powered coding assistant
- 💻 Answers only programming-related questions
- 🔐 Secure API key handling using environment variables
- 🌐 Web-based chat interface
- 🚫 Blocks non-technical questions
- ⚡ Lightweight Flask backend
- 🔒 No secrets stored in the repository

---

## 🛠 Tech Stack

- Python
- Flask
- OpenRouter API
- HTML / CSS
- Git & GitHub
- Gunicorn (for deployment)

---

## 📂 Project Structure

```
DevBot/
│
├── app.py
├── requirements.txt
├── .gitignore
├── README.md
└── templates/
      └── index.html
```

---

## 🔑 Environment Setup (Important)

Create a `.env` file locally:

```
OPENROUTER_API_KEY=your_api_key_here
```

⚠️ Never upload `.env` to GitHub.  
The `.gitignore` file prevents this automatically.

---

## ▶️ Run Locally

### 1️⃣ Install dependencies

```
pip install -r requirements.txt
```

### 2️⃣ Run the application

```
python app.py
```

### 3️⃣ Open in browser

```
http://127.0.0.1:5000
```

---

## 🌍 Deployment

DevBot can be deployed on:

- Render
- Railway
- Heroku
- Any Python hosting platform

When deploying, configure the environment variable:

```
OPENROUTER_API_KEY
```

inside the hosting provider settings.

---

## 🔐 Security Practices

- API keys are stored in environment variables
- `.env` file is excluded from Git using `.gitignore`
- Previously exposed keys have been revoked
- Clean Git history maintained

---

## 📌 Future Improvements

- Chat history storage
- Database integration
- User authentication
- ChatGPT-style UI
- Code syntax highlighting
- Custom domain deployment

---

## 👨‍💻 Author

**Dharani**

GitHub:  
https://github.com/dharani25007-code

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

## 📢 Keywords

Python chatbot, Flask AI app, OpenRouter integration, coding assistant, web-based AI bot
