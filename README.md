# 🤖 AI Task Scheduler (No-Code) – Built with n8n, ChatGPT & Google Calendar

This project demonstrates a no-code AI workflow that automatically schedules tasks to Google Calendar using **n8n**, **OpenAI (ChatGPT)**, and **Google Calendar API**.

> 🚀 Built in 45 minutes to explore AI agent-based automation using n8n’s free trial.

---

## 🌟 Features

- 🧠 **AI Agent Brain**: Powered by ChatGPT using OpenAI API
- 💬 **Chat Trigger**: Workflow starts when a chat input is detected
- 📅 **Google Calendar Integration**: Automatically adds new events
- 🔁 **Dynamic Expressions**: JSON expressions define event timing (e.g., current time + 1 hour)

---

## 🔧 Tools Used

| Tool             | Purpose                               |
|------------------|----------------------------------------|
| [n8n](https://n8n.io)              | No-code workflow automation platform |
| [OpenAI](https://platform.openai.com) | AI agent to parse and understand tasks |
| Google Calendar API | Schedule tasks/events dynamically      |

---

## 🧠 Workflow Logic

1. **Trigger:** User sends a chat message
2. **AI Agent:** Uses ChatGPT to understand intent
3. **Google Calendar Node:** Adds an event (based on extracted time and task)
4. **Expressions Used:** `now` and `addHours(now, 1)` for start/end time

---

## 🖼️ Screenshots

| Workflow in n8n | Scheduled Event |
|------------------|-----------------|
| ![Workflow](./screenshots/workflow.png) | ![Calendar](./screenshots/event.png) |

---

## 📂 Files Included

- `workflow.json`: Importable n8n workflow
- `screenshots/`: Visuals for better understanding
- `README.md`: Overview and usage
- `walkthrough.md`: Step-by-step setup instructions (optional)

---

## 🎯 Outcome

- ✅ Completed the workflow without errors
- 🧠 Understood AI agent integration in no-code tools
- 📅 Successfully auto-scheduled events via ChatGPT

---

## ✨ Why This Matters

This project reflects how **AI + Automation + No-code tools** can streamline everyday productivity tasks like scheduling. It's especially useful for:
- Students & teams
- Productivity hackers
- AI workflow enthusiasts

---

## 📜 License

MIT

---

## 🙋‍♀️ Built by

**Satvika Gada**  
NextWork.org Student | AI Enthusiast  
[Portfolio Coming Soon]


