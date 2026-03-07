# 🤖 n8n Automation Projects

AI-powered automation workflows built with n8n.
Designed to demonstrate real-world automation skills for AI companies.

---

## 📋 Projects

### 1. 🗞️ AI News Digest Bot
Automatically fetches top tech news every morning, 
summarizes articles using Groq AI, and delivers a 
beautifully formatted HTML digest to your inbox daily.

**Tools:** n8n • NewsAPI • Groq AI (LLaMA 3.3) • Gmail  
**Concepts:** Schedule Trigger • HTTP Request • Code Node • Email Automation  
**File:** `workflows/dailyNews.json`

---

### 2. 📬 Smart Contact Form Handler
Receives form submissions via webhook, classifies messages 
with AI into Sales/Support/Partnership/Spam, assigns priority 
level, routes to correct team, auto-replies, and logs 
everything to Google Sheets.

**Tools:** n8n • Groq AI • Gmail • Google Sheets  
**Concepts:** Webhook • Switch Node • Priority Detection • Google APIs  
**File:** `workflows/contactForm.json`

---

## ⚙️ Setup Instructions

To use these workflows in your own n8n instance:

1. Import the JSON file via n8n → Workflows → Import
2. Replace these placeholders with your actual keys:
   - `YOUR_NEWSAPI_KEY` → free key at [newsapi.org](https://newsapi.org)
   - `YOUR_GROQ_API_KEY` → free key at [console.groq.com](https://console.groq.com)
3. Set up Gmail OAuth2 credentials in n8n
4. Set up Google Sheets OAuth2 credentials in n8n

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| n8n | Workflow automation (self-hosted via Docker) |
| Groq AI | LLM inference (LLaMA 3.3 70B) |
| NewsAPI | Tech news aggregation |
| Gmail API | Email automation |
| Google Sheets API | Data logging |
| JavaScript | Code nodes logic |

---

## 🔒 Security Note

All API keys have been replaced with placeholders.
Never push real API keys to public repositories.

---

## 👤 Author

**Sandeep Choudhary**  
📧 sandeepchoudhary0566@gmail.com  
🐙 [github.com/cybersphinx1008](https://github.com/cybersphinx1008)
