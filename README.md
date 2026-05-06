# Automation
📧 Email Automation (Auto Message Sender)

🚀 Overview

This project is a simple email automation system built using n8n.
It automatically sends predefined emails based on triggers like time schedules or events.

---

🎯 Features

- ⏰ Scheduled email sending
- 📤 Sends predefined messages automatically
- 🔁 Supports repeated/recurring emails
- ⚡ Fast and reliable workflow

---

🧰 Tech Stack

- n8n (Workflow Automation)
- SMTP / Gmail

---

⚙️ How It Works

1. A trigger (schedule/webhook) starts the workflow
2. n8n executes the email node
3. A predefined message is sent to the recipient

---

📂 Project Structure

email-automation/
│── workflows/
│    └── email-workflow.json
│── README.md
│── .gitignore

---

🛠️ Setup Instructions

1. Install n8n
2. Import the workflow JSON file
3. Configure your email credentials (SMTP/Gmail)
4. Activate the workflow

---

🔐 Environment Variables

EMAIL_USER=your-email@gmail.com
EMAIL_PASS=your-password

---

📌 Use Cases

- Sending reminders (meetings, tasks)
- Daily/weekly notifications
- Automatic alerts

---


---

📸 Demo

<img width="960" height="540" alt="image" src="https://github.com/user-attachments/assets/4237f1b6-bca4-452a-adbf-06f40dd185c8" />


---

🌟 Future Improvements

- Adding multiple recipients support
- Adding email templates
- Adding logging system
- usage of ai replies

---

📜 License

MIT License
