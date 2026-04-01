# 🚀 Lead Form Automation Workflow

## 📌 Overview

This project is an automated workflow designed to handle lead form submissions efficiently.
It categorizes incoming leads based on their budget and triggers automated actions using Gmail.

---

## ⚙️ Features

* 🔹 Automatically captures form submissions
* 🔹 Classifies leads into:

  * Low Budget
  * Medium Budget
  * High Budget
* 🔹 Sends automated emails via Gmail
* 🔹 Applies labels to emails for better organization
* 🔹 Fully scalable and customizable workflow

---

## 🧠 How It Works

1. A user submits a form
2. The workflow is triggered
3. A switch node evaluates the lead's budget
4. Based on the budget:

   * An email is sent via Gmail
   * A label is applied (Low / Medium / High)

---

## 🛠️ Tech Stack

* Workflow Automation Tool (e.g., n8n)
* Gmail API

---

## 📂 Project Structure

```
/workflow.json   # Main automation workflow
```

---

## 🚀 Getting Started

1. Import the `workflow.json` file into your automation tool
2. Connect your Gmail account
3. Activate the workflow
4. Start receiving and managing leads automatically

---

## 💡 Use Cases

* Lead generation systems
* Marketing automation
* CRM pre-processing
* Sales pipeline organization

---

## 👩‍💻 Author

Created by Aseel Arafah

---

## ⭐ Notes

This project is a great example of how automation can simplify lead management and improve response time.
