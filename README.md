# 🌅 Daily Quote Generator using n8n

An automated workflow built with **n8n** that retrieves a random inspirational quote from a free public API every day and sends it directly to **Telegram**.

This project demonstrates scheduled automation, REST API integration, JSON parsing, data transformation, and Telegram bot notifications using only free services.

---

## 📌 Overview

This workflow automatically performs the following tasks:

- Runs every day at a scheduled time.
- Retrieves a random inspirational quote from a public API.
- Formats the quote into a clean and readable message.
- Sends the quote directly to Telegram.

---

## 🚀 Features

- ⏰ Daily scheduled execution
- 💬 Random inspirational quote
- 📲 Telegram notification
- 🌐 Free public API
- 🔑 No API key required
- 💯 Fully automated

---

## 🛠 Tech Stack

- n8n
- HTTP Request
- DummyJSON API
- Telegram Bot API

---

## 📂 Workflow

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

## ⚙️ Workflow Explanation

### 1. Schedule Trigger

Automatically runs the workflow every day at the configured time.

---

### 2. HTTP Request

Retrieves a random inspirational quote from the DummyJSON API.

**API Endpoint**

```
https://dummyjson.com/quotes/random
```

**Method**

```
GET
```

**Authentication**

```
None
```

---

### 3. Edit Fields (Set)

Formats the API response into a readable Telegram message.

Example Output:

```
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

Sends the formatted quote directly to your Telegram account.

---

## 📁 Project Structure

```
Daily-Quote-Generator/
│
├── README.md
├── workflow.json
└── screenshots/
    ├── workflow.png
    ├── telegram-output.png
    └── workflow-execution.png
```

---

## 📸 Screenshots

Include the following screenshots:

- Workflow Editor
- Successful Workflow Execution
- Telegram Output

Example:

```
screenshots/
    workflow.png
    workflow-execution.png
    telegram-output.png
```

---

## 💡 Use Cases

- Daily motivation
- Morning productivity routine
- Personal development
- Telegram automation
- Learning REST API integration with n8n
- Portfolio automation project

---

## 🔮 Future Improvements

- Support multiple quote categories
- Filter quotes by author
- Save quotes to Google Sheets
- Email daily quotes
- Publish quotes to Discord or Slack
- Generate AI-powered reflections for each quote
- Support multilingual quotes

---

## 📚 What I Learned

This project helped me gain hands-on experience with:

- Workflow automation using n8n
- REST API integration
- JSON parsing
- Data transformation
- Telegram Bot integration
- Scheduled workflows

---

## 🏷 Skills Demonstrated

- n8n
- Workflow Automation
- REST API
- HTTP Request
- JSON Parsing
- Data Transformation
- Telegram Bot API
- Scheduled Automation
- No-Code / Low-Code Development

---

## 📄 License

This project is licensed under the MIT License.

---

⭐ If you found this project helpful, consider giving it a star!
