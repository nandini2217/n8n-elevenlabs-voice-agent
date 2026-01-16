# 🎙️ n8n ElevenLabs Voice Agent

AI voice agent built with **n8n** and **ElevenLabs** that understands conversational instructions and automates calendar management.

![n8n Workflow](n8n-workflow-image)

---

## 🚀 Project Overview

This project demonstrates how an **AI-powered automation agent** can manage calendar tasks end-to-end.

Whatever the user tells the agent (meeting time, date, reminder, etc.), the workflow:

* 🧠 Interprets the instruction
* 📆 Creates or updates a Google Calendar event
* 📧 Sends an email reminder **10 minutes before the event**

All of this is handled automatically using **n8n workflows**.

---

## ✨ Features

* 🗣️ Conversational / agent-style input
* 📆 Google Calendar integration
* 📧 Automated email reminders
* ⏱️ Reminder sent 10 minutes before the event
* 🔁 Fully automated workflow
* 🧩 Built entirely using n8n workflow automation
* 🔐 Secure credential handling (no hardcoded secrets)

---

## 🛠️ Tech Stack

* **n8n** – Workflow automation
* **ElevenLabs** – Voice / conversational input
* **Google Calendar API**
* **Email Service** – SMTP / Gmail
* **AI Agent Logic**
* **Webhook / Trigger Nodes**

---

## 🔄 How It Works

1. User gives an instruction to the agent
   **Example:** *"Schedule a meeting tomorrow at 3 PM"*
2. n8n processes the conversational input
3. The event is created or updated in Google Calendar
4. An email reminder is automatically sent **10 minutes before the event**

---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository

```bash
git clone <repository-url>
```

### 2️⃣ Import Workflow into n8n

1. Open **n8n**
2. Click **Import Workflow**
3. Upload:

   ```
   workflows/calendar-agent-workflow.json
   ```

### 3️⃣ Configure Credentials

Add the following credentials in **n8n Credentials Manager**:

* ✅ Google Calendar (OAuth)
* ✅ Email (SMTP / Gmail)

---

## 🔐 Security Notes

* ❌ No API keys are included in this repository
* 🔐 All credentials are securely managed via **n8n Credentials Manager**
* ✅ Safe to use in production with proper OAuth configuration

---

## ⭐ Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🛠️ Feel free to improve or extend the workflow

---

Happy automating! 🚀
