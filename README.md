# 🤖 Python Chatbot using Gemini API

A simple **command-line chatbot** built in Python using **Google Gemini API**.  
This project demonstrates how to build a chatbot that chats with users using Gemini's **`gemini-1.5-flash`** model.

---

## 🚀 Features
- 💬 Interactive chat directly in the terminal  
- 🔐 Secure API key handling via `.env`  
- ⚡ Powered by **Gemini API**  
- 🐍 Lightweight Python implementation  

---

## 🛠️ Setup Instructions

### 1️⃣ Clone the repository
```bash
git clone https://github.com/DeveloperMK07/gemini-conversations
cd python-gemini-chatbot
```
---
2️⃣ Create a virtual environment (recommended)
python -m venv venv
### Activate it
source venv/bin/activate    # Linux / Mac
venv\Scripts\activate       # Windows

---
3️⃣ Install dependencies
```bash
pip install -r requirements.txt
```
---
4️⃣ Set up .env file
```bash
Create a .env file in the root folder and add your Gemini API key:

GEMINI_API_KEY=your_api_key_here
```

👉 Get your free key from Google AI Studio
.
---
5️⃣ Run the chatbot
```bash
python main.py
```
🖥️ Example Run
```bash
Chatbot ready! Type 'quit' to exit.

You: Hello
Chatbot: Hi there! How can I help you today?

You: quit
Chatbot: Goodbye!
```
---
⚠️ Notes

Never commit your .env file to GitHub

Add .env to .gitignore

Free tier API key works best with gemini-1.5-flash
