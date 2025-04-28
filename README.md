BrightGlow Skincare Automation
This repository contains full automation workflows built using n8n.io for an e-commerce skincare brand called BrightGlow Skincare.

📂 Workflows Overview
Sales Report Automation
- Schedule weekly report.
- Summarize total orders, total revenue, best-selling product.
- Send summary and Google Sheets link via Gmail.

Stock Notification System
- Schedule hourly stock check.
- Alert team if product inventory drops below threshold (10 pcs).
- Send stock alert email automatically.

Customer Service Auto-Reply (RAG System)
- Auto-reply customer questions based on FAQ knowledge base.
- Use OpenAI GPT-4o mini + Pinecone vector store retrieval.
- Log all customer queries to Google Sheets for further analysis.

🛠️ Technologies Used
n8n.io – Automation platform
OpenAI API – AI Language model
Pinecone – Vector Database
Google Sheets – Storage and reporting
Gmail API – Email automation
Meta Graph API – Instagram/Facebook DM automation

🚀 How to Use
Clone or download this repository.
Import JSON workflows into your n8n instance.
Configure your credentials for:
Google Sheets
OpenAI API
Gmail API
Meta API (optional)
Activate workflows and enjoy automation!
