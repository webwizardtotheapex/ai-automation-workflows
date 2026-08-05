# 🏡 Real Estate Lead Intake

An AI-powered lead intake and qualification workflow built with **n8n** that captures real estate inquiries, analyzes lead information, stores data, and automatically notifies both the business owner and prospective client.

---

## 📌 Overview

This workflow automates the first stage of the real estate sales process.

When a potential client submits their information, the workflow validates the data, records the lead, sends notifications to the sales team, confirms the submission to the client, and triggers WhatsApp alerts for immediate follow-up.

---

## ✨ Features

- AI-powered lead qualification
- Captures client information
- Stores leads in Google Sheets
- Sends confirmation email to the client
- Sends internal notification email
- Slack notification
- Twilio WhatsApp notification
- Appointment booking confirmation
- Fully automated

---

## 🛠 Tech Stack

- n8n
- OpenAI
- Gmail API
- Google Sheets
- Slack
- Twilio WhatsApp
- Webhooks
- HTTP Requests

---

## ⚙️ Workflow Process

```text
Client Form
      │
      ▼
Receive Lead
      │
      ▼
AI Qualification
      │
      ▼
Save to Google Sheets
      │
      ├──────────────► Slack Notification
      │
      ├──────────────► Email to Client
      │
      ├──────────────► Internal Email
      │
      └──────────────► WhatsApp Alert
```

---

## 📸 Screenshots

See the screenshots inside this project folder.

---

## 💡 Use Cases

- Real Estate Agencies
- Property Consultants
- Mortgage Companies
- Sales Teams
- Lead Qualification

---

## 🔒 Security

All credentials and API keys have been removed before publishing.

---

## 👨‍💻 Author

**Isa Hassan**

AI Automation Engineer

🌐 https://soldevhassan.com

📧 webwizardtotheapex@gmail.com

💼 https://linkedin.com/in/isa-hassan-automation

🐦 https://x.com/SolDevHassan

💻 https://github.com/webwizardtotheapex
