# 🔍 LangChain Chatbot with Web Search

This project is a Streamlit-based chatbot powered by LangChain and Groq’s blazing-fast LLaMA 3 model. It uses tools like **Wikipedia**, **ArXiv**, and **DuckDuckGo** to fetch reliable information and answer your queries in real-time.

---

## 🚀 Features

- ✅ Chat interface built with **Streamlit**
- 🧠 Uses **LangChain agents** with `CHAT_ZERO_SHOT_REACT_DESCRIPTION`
- 🔎 Integrated tools: 
  - Wikipedia (via LangChain)
  - ArXiv (for research papers)
  - DuckDuckGo (for general web search)
- ⚡ Powered by **Groq API** using **LLaMA 3**
- 🧵 Streaming responses with typing-like effect
- 🔐 Secure API key handling using `.env`

---

## 📸 Screenshot

![screenshot](https://github.com/your-username/your-repo-name/assets/demo-image.png)  
*(optional — add a screenshot of your chatbot UI)*

---

## 📦 Requirements

- Python 3.9+
- `streamlit`
- `langchain`
- `langchain_groq`
- `python-dotenv`
- `duckduckgo-search`
- `wikipedia`

---

## 🛠 Installation

### 1. Clone the repo

```bash
git clone https://github.com/<your-username>/LangChain-SearchBot.git
cd LangChain-SearchBot