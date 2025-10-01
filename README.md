# AI Gmail Responder: Draft Email Replies

**Automatically drafts professional replies to incoming Gmail emails using AI.**  

This workflow is built with **n8n** and uses **Cohere’s free AI model** to help you save time by generating draft replies without any cost.  

---

## 🚀 Features
- Automatically reads new Gmail messages.
- Determines if an email needs a response.
- Drafts a professional, human-like reply using AI.
- Creates a draft in Gmail ready to send.
- Keeps your tone warm, concise, and business-casual.
- Free to use – powered by Cohere’s free AI plan.  

---

## 💻 Tech Stack
- [n8n](https://n8n.io/) – Workflow automation tool
- [Gmail API](https://developers.google.com/gmail/api) – To read emails and create drafts
- [Cohere AI](https://cohere.com/) – AI language model (free tier)
- JSON workflow file for easy import

---

## ⚡ How to Use

### 1. Import Workflow
1. Download the workflow JSON file: `ai-gmail-responder.json`.  
2. Open your n8n instance.  
3. Go to **Workflows → Import → Import from file** and upload the JSON file.

### 2. Set Up Credentials
- **Gmail OAuth2** – Connect your Gmail account.  
- **Cohere API Key** – Sign up on [Cohere](https://cohere.com/) for a free API key and connect it in n8n.

### 3. Activate Workflow
- Once credentials are connected, activate the workflow.  
- Incoming emails will automatically trigger the AI to draft replies.

---

## 📌 Notes
- This workflow **does not send emails automatically**; it creates drafts so you can review before sending.  
- For yes/no questions, the AI provides **both affirmative and negative options**.  
- Uses **Cohere free API plan**, so no payment is required.   

---

## 💡 Tip
You can customize the AI prompt in the workflow to match your preferred tone, style, or language.  

---

**Enjoy your AI-powered Gmail assistant!**
