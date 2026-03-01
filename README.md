# 🤖 Daily Reminder Bot using n8n

An automated Daily Reminder Bot built with n8n that sends scheduled reminders to users via Email, Telegram, Slack, or other integrations. This project demonstrates workflow automation, scheduling, and real-world productivity enhancement using a no-code/low-code automation platform.

---

## 📌 Table of Contents

* Overview
* Features
* Tech Stack
* Workflow Architecture
* Installation
* Usage
* Workflow Nodes Explanation
* Use Cases
* Project Structure
* Future Improvements
* Author

---

## 🧠 Overview

The Daily Reminder Bot is an automation workflow designed to send reminders automatically at scheduled times. It eliminates the need for manual tracking of tasks, meetings, and deadlines.

Using n8n's Cron Trigger and notification integrations, the bot ensures reliable and consistent reminders.

This project demonstrates:

* Workflow automation
* Task scheduling
* API integrations
* Real-world automation use case

---

## ✨ Features

* ⏰ Automated daily reminders
* 📅 Time-based scheduling using Cron Trigger
* 📩 Sends reminders via Email / Telegram / Slack
* 🔄 Fully automated workflow
* ⚡ No manual intervention required
* 🧩 Easy to customize
* 🌐 Scalable workflow design

---

## 🛠️ Tech Stack

| Tool                  | Purpose                       |
| --------------------- | ----------------------------- |
| n8n                   | Workflow automation           |
| Cron Node             | Scheduling reminders          |
| Email Node            | Sending email reminders       |
| Telegram / Slack Node | Sending instant notifications |
| Webhook (optional)    | External integrations         |

---

## 🔄 Workflow Architecture

```
Cron Trigger Node
        │
        ▼
Set Reminder Message
        │
        ▼
Notification Node (Email / Telegram / Slack)
        │
        ▼
Reminder Sent Successfully
```

---

## ⚙️ Installation

### Step 1: Install n8n

Using npm:

```bash
npm install n8n -g
```

Or using Docker:

```bash
docker run -it --rm \
-p 5678:5678 \
n8nio/n8n
```

---

### Step 2: Start n8n

```bash
n8n
```

Open browser:

```
http://localhost:5678
```

---

### Step 3: Import Workflow

1. Open n8n dashboard
2. Click **Import Workflow**
3. Upload the workflow JSON file
4. Configure credentials

---

## ▶️ Usage

1. Set reminder time in Cron Node
2. Configure Email or Telegram credentials
3. Customize reminder message
4. Activate workflow
5. Bot will send reminders automatically

---

## 🔎 Workflow Nodes Explanation

### 1. Cron Trigger Node

Triggers workflow at scheduled time daily.

### 2. Set Node (Optional)

Defines reminder message content.

Example:

```
Reminder: Complete your daily tasks.
```

### 3. Notification Node

Sends reminder via:

* Email
* Telegram
* Slack

---

## 📂 Project Structure

```
daily-reminder-bot-n8n/
│
├── workflow.json
├── README.md
└── screenshots/
    └── workflow.png
```

---

## 💡 Use Cases

* Task reminders
* Study reminders
* Meeting alerts
* Medication reminders
* Habit tracking
* Productivity automation

---

## 🎯 Project Impact

This project demonstrates:

* Automation skills
* Workflow design
* Scheduling systems
* Integration with communication platforms

This is highly relevant for roles such as:

* AI Engineer
* Automation Engineer
* DevOps Engineer
* Software Developer

---

## 🔮 Future Improvements

* Add database support
* Multi-user reminder system
* Web dashboard
* AI-based smart reminders
* Mobile app integration

---

## 📷 Screenshot

(Add workflow screenshot here)

Example:

```
screenshots/workflow.png
```

---

## 👩‍💻 Author

Ananthi Thiyagarajan

---

## ⭐ Support

If you like this project, please give it a ⭐ on GitHub.
