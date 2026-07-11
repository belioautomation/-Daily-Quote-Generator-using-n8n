# 🌅 Daily Quote Generator using n8n

## 📌 Project Overview

Daily Quote Generator is an automated workflow built with **n8n**, the **DummyJSON API**, and **Telegram**. It retrieves a random inspirational quote each day, formats it into a readable message, and sends it directly to Telegram.

Built as part of my **30-Day n8n Automation Portfolio**, this project demonstrates scheduled automation, REST API integration, JSON data processing, and automated messaging using free services.

---

## 🎯 Objectives

* Automate daily inspirational quote delivery
* Integrate a public REST API with n8n
* Format API responses into user-friendly messages
* Deliver daily Telegram notifications
* Build a portfolio-ready automation workflow

---

## 🏗️ Workflow Architecture

```text
Schedule Trigger
        │
        ▼
HTTP Request
        │
        ▼
Edit Fields (Set)
        │
        ▼
Telegram
```

---

## ⚙️ Workflow Implementation

### 1. Schedule Trigger

Runs the workflow automatically every day at a scheduled time.

---

### 2. HTTP Request

Retrieves a random inspirational quote from the DummyJSON API.

Example endpoint:

```text
https://dummyjson.com/quotes/random
```

Method:

```text
GET
```

Authentication:

```text
None
```

---

### 3. Edit Fields (Set)

Formats the API response into a readable Telegram message.

Example:

```text
🌅 Good Morning!

💬 Daily Inspirational Quote

"Success is not final, failure is not fatal: it is the courage to continue that counts."

— Winston Churchill

📅 July 01, 2026

Have an amazing day! 🚀

🤖 Generated automatically with n8n.
```

---

### 4. Telegram

Sends the formatted quote directly to Telegram.

---

## 🛠️ Technologies Used

* n8n
* DummyJSON API
* HTTP Request
* Telegram Bot API

---

## 📁 Repository Structure

```text
Daily-Quote-Generator/
│
├── README.md
├── workflow.json
│
├── screenshots/
│   ├── workflow.png
│   ├── telegram-output.png
│   └── workflow-execution.png
│
└── assets/
```

---

## 📸 Screenshots

Include the following screenshots:

* Complete Workflow
* Workflow Execution
* Telegram Output

---

## 🚀 Key Features

* ✅ Scheduled Workflow Automation
* ✅ Random Daily Quote Retrieval
* ✅ REST API Integration
* ✅ Telegram Notifications
* ✅ JSON Data Processing
* ✅ Fully Automated Workflow
* ✅ Uses Free Public API

---

## 🎓 Lessons Learned

Through this project, I gained experience in:

* Building scheduled automation workflows
* Integrating REST APIs with n8n
* Processing JSON responses
* Formatting API data for messaging
* Automating Telegram notifications
* Designing reliable daily automation workflows

---

## 📈 Impact

This workflow automates the delivery of daily inspirational quotes, eliminating the need for manual sharing while demonstrating practical API integration, scheduled automation, and message formatting with n8n.

---

## 📜 License

MIT License

---

## 👨‍💻 Author

**Belio C. Sinangote**

BS Information Technology Student
Cebu Technological University (CTU)

GitHub: [https://github.com/belioautomation](https://github.com/belioautomation)

This project is part of my **30-Day n8n Automation Portfolio**, showcasing practical workflow automation using n8n, APIs, and automation best practices.
