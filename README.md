# AI Payment Reminder Agent

An AI-powered automation tool that calls and sends SMS reminders for upcoming payments using **Retell AI** and **Twilio**.

---

## 📌 Problem Statement
Businesses lose revenue due to missed payments caused by forgetfulness or lack of timely reminders.  
This solution automates the payment reminder process using AI voice calls and SMS.

---

## 🛠 Tech Stack
- **Retell AI** – Automated voice calls
- **Twilio** – SMS reminders
- **Node.js** – Backend automation
- **CSV Parser** – Reads customer data
- (Optional) **OpenAI API** – For personalized messages

---

## 🔄 Workflow
1. Upload CSV with customer data  
2. Node.js processes each entry  
3. Retell AI sends a voice call  
4. Twilio sends an SMS reminder  
5. Log saved for tracking

**Workflow Diagram:**  
![Workflow](docs/workflow.png)

---

## 🚀 How to Run
```bash
# Install dependencies
npm install

# Run script
node index.js
