<p align="center">
  <img src="assets/logo-horizontal.png" alt="OXIVAR AI" width="340">
</p>

<h1 align="center">AI Lead Management System</h1>

<p align="center">
An AI-powered workflow that automates lead collection, response generation, email communication, and lead storage using n8n, Google Gemini, Gmail, and Google Sheets.
</p>

<p align="center">

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-FF6D5A?logo=n8n&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-4285F4?logo=google&logoColor=white)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-34A853?logo=googlesheets&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green)

</p>

---

# 📌 Overview

The **AI Lead Management System** is an intelligent automation workflow designed to eliminate manual lead handling.

Once a visitor submits the contact form, the system automatically:

- Collects lead information
- Generates an AI-powered response using Google Gemini
- Stores the lead in Google Sheets
- Sends a professional HTML confirmation email
- Notifies the business owner instantly

The entire process is fully automated with **n8n**, reducing manual work while improving customer response time.

---

# 📚 Table of Contents

- Features
- Tech Stack
- Workflow
- Screenshots
- Project Structure
- Installation
- Business Benefits
- Future Improvements
- About OXIVAR AI

---

# ✨ Features

- 🤖 AI-generated customer replies
- 📋 Automatic lead collection
- 📊 Google Sheets integration
- 📧 Professional HTML email confirmation
- 🔔 Instant business owner notifications
- ⚡ End-to-end automation with n8n
- 🔒 Secure credential management

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| n8n | Workflow Automation |
| Google Gemini | AI Response Generation |
| Gmail API | Email Automation |
| Google Sheets API | Lead Storage |

---

# 🔄 Workflow

```text
Customer Form
      │
      ▼
Generate AI Response
      │
      ▼
Prepare Lead Data
      │
      ▼
Save Lead into Google Sheets
      ├────────► Send Confirmation Email
      └────────► Notify Business Owner
```

---

# 📸 Screenshots

## Workflow

<p align="center">
<img src="screenshots/workflow.png" width="100%">
</p>

---

## Contact Form

<p align="center">
<img src="screenshots/form.png" width="100%">
</p>

---

## Customer Confirmation Email

<p align="center">
<img src="screenshots/email.png" width="100%">
</p>

---

## Google Sheets Database

<p align="center">
<img src="screenshots/google-sheet.png" width="100%">
</p>

---

# 📂 Project Structure

```text
ai-lead-management-system
│
├── assets
│   └── logo-horizontal.png
│
├── screenshots
│   ├── workflow.png
│   ├── form.png
│   ├── email.png
│   └── google-sheet.png
│
├── workflows
│   └── ai-lead-management-system.json
│
├── LICENSE
├── README.md
└── .gitignore
```

---

# 🚀 Installation

1. Import the workflow into n8n.
2. Configure your own credentials:
   - Google Gemini API
   - Gmail
   - Google Sheets
3. Update the Google Sheet destination.
4. Activate the workflow.
5. Start receiving AI-powered leads automatically.

---

# 💼 Business Benefits

- Reduce manual work
- Faster customer response time
- Professional customer communication
- Centralized lead database
- AI-powered workflow
- Easily customizable and scalable

---

# 🔮 Future Improvements

- CRM Integration
- Dashboard & Analytics
- Lead Status Tracking
- Multi-language Support
- PDF Proposal Generator
- Calendar Booking Integration

---

# 👨‍💻 About OXIVAR AI

**OXIVAR AI** develops intelligent automation systems that help businesses streamline operations, improve customer engagement, and eliminate repetitive tasks through AI-powered workflows.

This repository is part of the **OXIVAR AI Automation Portfolio**.

---

<p align="center">

### Built with ❤️ using n8n & Google Gemini

© 2026 OXIVAR AI

</p>
