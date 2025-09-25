# Salesforce Smart Case Routing 🚀
# Problem Statement
In traditional customer support systems, all incoming cases are routed manually or using simple rules (such as based on keywords or customer type). This approach has several problems:
• **High-priority or negative cases may be delayed**, as they are not automatically identified.
• **Manual routing increases workload** for managers and support leads.
• **Customer dissatisfaction** grows when urgent cases are not resolved quickly.
Organizations need a **smart, automated, and scalable solution** to:
  • Detect **customer sentiment** (Positive, Neutral, Negative) from case descriptions.
  • Assign urgent/negative cases to the **right team** immediately.
  • Provide **real-time visibility** into sentiment and priority trends for managers.

---

This project implements **AI-powered smart case routing** in Salesforce using **Apex, Flows, and Dashboards**.  
When a new Case is created, the system automatically analyzes its **sentiment** (Positive, Neutral, Negative) and **routes** it to the right support team.  

---

## 📌 Features
- **Sentiment Analysis** on Case Description (using Hugging Face API / Einstein Sentiment).
- **Automatic Routing** of cases to Junior or Senior Support queues.
- **Notifications** for high-priority negative cases.
- **Dashboard & Reports** for sentiment trends and escalations.
- **Test Class** with >75% coverage for Apex code.

---

## 🏗️ Project Structure
