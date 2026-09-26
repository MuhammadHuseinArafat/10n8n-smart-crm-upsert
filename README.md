# 10n8n-smart-crm-upsert

# 🧠 Project 11: Real-Time CRM Alert System via Telegram API

![n8n](https://img.shields.io/badge/n8n-FF6D5W?style=for-the-badge&logo=n8n&logoColor=white)
![Telegram API](https://img.shields.io/badge/Telegram_API-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)

## 📖 Overview
An extension of the Smart CRM Upsert pipeline. This module integrates the n8n workflow with the Telegram Bot API to deliver real-time, context-aware notifications to sales teams whenever a lead is generated or updated in the database.

## 🏢 The Business Problem
Sales teams often miss hot leads because they rely on passively checking databases or spreadsheets. Delayed response times significantly drop conversion rates. Furthermore, sales reps need to know immediately if they are dealing with a brand-new prospect or an existing lead updating their information.

## 💡 The Solution
A dynamic notification routing system that listens to database operations and triggers instantaneous Telegram alerts.
✅ **Context-Aware Routing:** Utilizes the output from the Upsert logic (Append vs. Update) to trigger different notification templates.
✅ **Data Parsing:** Extracts raw JSON payloads from the initial Webhook using Cross-Node Referencing to construct readable alert messages.
✅ **Instant Delivery:** Pushes formatted alerts directly to the sales team's Telegram group within milliseconds.

<img width="1016" height="537" alt="image" src="https://github.com/user-attachments/assets/d0b37fab-bdc6-40b9-b0bd-49203d65ac2f" />

the message 
<img width="720" height="1600" alt="image" src="https://github.com/user-attachments/assets/ad332608-7e8b-487d-97bb-490be218d6a0" />



## 📈 Business Value
- **Zero Latency Lead Routing:** Sales reps can contact hot leads within seconds of form submission.
- **Improved Context:** Reps know exactly what changed in a lead's profile before making a call.
- **Operational Efficiency:** Eliminates the need for manual database monitoring.
