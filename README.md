# n8n-elevenlabs-voice-agent
AI voice agent built with n8n and ElevenLabs

An intelligent automation agent built with n8n that understands user instructions and automatically:
  📅 Creates or updates Google Calendar events
  ⏰ Sends email reminders 10 minutes before events
  🎙️ Works with conversational / agent-style input

🔁 Fully automated workflow
🚀 Project Overview
   This project demonstrates how an AI-powered agent can manage calendar tasks automatically.
   Whatever the user tells the agent (meeting time, date, reminder, etc.), the workflow:
   Interprets the instruction
   Updates Google Calendar
   Triggers an email reminder 10 minutes before the event

✨ Features
   🗣️ Conversational agent input
   📆 Google Calendar integration
   📧 Automated email reminders
   ⏱️ Reminder sent 10 minutes before event
   🧩 Built entirely using n8n workflow automation
   🔐 Secure credential handling (no hardcoded secrets)

🛠️ Tech Stack
   n8n – Workflow automation
   Google Calendar API
   Email service (SMTP / Gmail)
   AI Agent logic
   Webhook / Trigger nodes

🔄 How It Works
   User gives an instruction to the agent
   Example: “Schedule a meeting tomorrow at 3 PM”
   n8n processes the input
   Event is created/updated in Google Calendar
   A reminder email is automatically sent 10 minutes before the event

⚙️ Setup Instructions
1️) Clone the Repository

2️) Import Workflow into n8n
Open n8n
Click Import Workflow
Upload:
workflows/calendar-agent-workflow.json

3️)Configure Credentials
Add the following credentials in n8n:
Google Calendar OAuth
Email (SMTP / Gmail)

🔐 Security Notes
No API keys are included in this repository
All credentials are handled via n8n credentials manager
Safe to use in production with proper OAuth setup

⭐ If you like this project
Give it a ⭐ and feel free to fork or improve it!
