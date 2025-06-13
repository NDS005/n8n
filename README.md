# 🤖 Google QA Agent using n8n + Groq LLM

This project is a no-code AI agent that answers real-world questions by integrating a Large Language Model (LLM) with real-time web data. Built using [n8n](https://n8n.io/), this agent fetches Google search results using SERP API and passes them to Groq's LLaMA model for intelligent summarization.

---

## 🌍 Objective

To create an autonomous agent that answers user queries based on fresh and relevant information from the web.

---

## 🧠 How It Works

1. **Input**: The user provides a query like *"Who won the IPL 2024 final?"*
2. **Web Search**: The agent uses **SERP API** to scrape the top Google search results for that question
3. **LLM Reasoning**: It then sends this data to **Groq LLaMA** via an API call
4. **Response**: The LLM processes the context and returns a clean, summarized answer

---

## ⚙️ Tools & Technologies

* **n8n** (Visual workflow builder)
* **Groq LLaMA (via HTTP Request)**
* **SERP API** for Google search
* Optional: Email, Telegram, Notion, or Google Sheets for output

---

## 📸 Screenshot

<img width="409" alt="image" src="https://github.com/user-attachments/assets/928eca42-ff6c-4b92-a21f-bcaaec12f561" />
<img width="806" alt="image" src="https://github.com/user-attachments/assets/8e7c4bdc-0e3f-4720-8487-1859a041914a" />


## 🧪 How to Try It

1. Import the workflow in your n8n instance (create it visually if JSON isn't available)
2. Add your **Groq API key** and **SERP API key**
3. Trigger the workflow manually or through a webhook
4. Watch the output or route it to email, Telegram, or storage

---


