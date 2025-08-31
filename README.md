# 🤖 AI Chatbot with n8n  

## 📌 Overview  
This project demonstrates how to build a **custom AI-powered chatbot** using **n8n**, integrated with **LLMs (Google Gemini / OpenAI / Ollama)**.  
The chatbot can:  
- Answer user queries in real-time  
- Maintain context using memory  
- Handle workflow automation (like planner tasks, reminders, or data retrieval)  
- Be embedded into a **web chat interface**  

The chatbot is designed as a **modular workflow** in n8n, making it easy to extend with external APIs, databases, and automation features.  

---

## 🛠️ Tech Stack  
- **n8n** – Workflow automation & chatbot orchestration  
- **Google Gemini / OpenAI / Ollama** – LLM-powered responses  
- **Webhook & Gradio UI** – User-friendly web chat interface  
- **Custom Memory System** – To keep chat context  
- **Planner Integration** – Daily task tracking and reminders  

---

## ✨ Features  
✔️ Real-time AI chat responses  
✔️ Task planner integration (daily routines, reminders, schedules)  
✔️ Memory support for contextual conversations  
✔️ Webhook-based deployment (accessible via browser)  
✔️ Extendable with APIs (Google, Notion, Calendar, etc.)  

---

## 📂 Project Structure  
```
AI-Chatbot-n8n/
├── workflows/
│   ├── chatbot-workflow.json   # n8n chatbot workflow export
│   └── planner-workflow.json   # Task planner workflow export
├── screenshots/
│   ├── Chat bot 2.png
│   ├── Chat bot 2.1.png
│   ├── n8n Chat bot.png
│   └── access planner output.png
├── README.md                   # Documentation
```

---

## 🖼️ Demo Screenshots  

### 🔹 Chatbot Workflow in n8n  
![Chatbot Workflow](screenshots/n8n%20Chat%20bot.png)  

### 🔹 Web Chat Interface  
![Web Chat](screenshots/Chat%20bot%202.png)  
![Web Chat 2](screenshots/Chat%20bot%202.1.png)  

### 🔹 Planner Integration  
![Planner Output](screenshots/access%20planner%20output.png)  

---

## 🚀 How to Run  

### 1️⃣ Setup n8n  
- Install n8n locally or on cloud ([Docs](https://docs.n8n.io/))  
- Import the chatbot workflow JSON file into n8n  

### 2️⃣ Configure LLM Integration  
- Connect your preferred LLM (Google Gemini, OpenAI, or Ollama)  
- Add your API keys in the respective nodes  

### 3️⃣ Deploy Chatbot  
- Expose workflow via **Webhook**  
- Open the chat interface in browser  
- Start interacting with your AI agent 🎉  

---

## 🎯 Learning Outcomes  
- How to design **AI workflows** with n8n  
- How to integrate **LLMs into automation pipelines**  
- How to build a **personal AI assistant with memory + planner features**  

---

## 🤝 Connect With Me  
- LinkedIn: [Sheetal Kothari](https://www.linkedin.com/in/13-sheetal-kothari/)  
