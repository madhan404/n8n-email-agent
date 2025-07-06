# 🚀 n8n Email Agent – Telegram Integrated AI Workflow

Hi there! 👋  
This is my **self-hosted AI-powered n8n agent** that can:
- 📩 Receive requests via **Telegram Bot**
- 📧 Send emails via **Brevo (Sendinblue)**
- 🤖 Process AI queries using **DeepSeek R1** in **LM Studio (local LLM)**
- 💬 Instantly reply back to the user in **the same Telegram chat**

And the best part? Built with **₹0 cost – fully self-hosted & free tools!** 💸

---

![Status](https://img.shields.io/badge/Build-Zero%20Cost-brightgreen)
![Tech](https://img.shields.io/badge/Built%20With-n8n%20%7C%20Telegram%20%7C%20MongoDB%20%7C%20DeepSeek%20R1%20%7C%20Brevo-blue)
![By](https://img.shields.io/badge/Author-Madhanraj%20S-yellow)

---

## 💡 Workflow Overview
1. **Telegram Bot** receives user request.
2. **n8n Docker (Localhost)** processes the workflow.
3. **MongoDB** stores session, chat ID, and chat memory.
4. **DeepSeek R1 in LM Studio** generates the AI response.
5. **Brevo** triggers email delivery.
6. **HTTP Node** sends confirmation back to the user via Telegram.

---

## 📥 How to Use
1. Import the provided `.json` file into your n8n instance.
2. Set up your:
   - Telegram Bot Token
   - MongoDB connection
   - LM Studio local endpoint
   - Brevo API Key
3. Run the workflow.
4. Send a message to your Telegram bot and watch the magic happen! ✨

---

## 🔗 Live Demo Flow
> 📄 [Check out my LinkedIn post here!](Add-your-LinkedIn-post-link-here)

---

## 🚀 Tech Stack
- n8n (Docker Localhost)
- Telegram Bot
- MongoDB
- DeepSeek R1 (LM Studio)
- Brevo (Free Email API)

---

## 💬 Connect with Me
If you try it out or want to build something similar, feel free to reach out!  
Happy to connect with others working on **AI agents, automations, and no-code platforms.** 😎

---

### 📂 Project Badge
[![Madhanraj's n8n Project](https://img.shields.io/badge/My%20Project-n8n%20Email%20Agent-blue)](https://github.com/madhan404/n8n-email-agent)

---

*Built with 💙 by Madhanraj S ([@madhan404](https://github.com/madhan404))*
