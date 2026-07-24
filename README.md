# 🚀 Telegram AI Agent using n8n & Open-Source LLMs

An event-driven, multi-model AI conversational agent integrated with Telegram using **n8n automation workflow engine** and powered by **Groq (`Llama 3.1 8B`) / Google Gemini API**.

### 📹 Live Project Demo
📽️ **[Watch the Live Project Demo Video on MyDrive](https://drive.google.com/file/d/1nx57kgyBRlljU6tYTBtox212M_xb1sCu/view?usp=drive_link)

---

## 📌 Project Overview
This project demonstrates how to build and deploy a low-latency, scalable AI assistant inside Telegram. It uses webhooks to catch incoming messages instantly, orchestrates context handling via n8n's AI Agent node, and queries high-speed LLMs to deliver natural language responses back to the user.

---

## ⚙️ Key Features
- **Event-Driven Architecture:** Uses Telegram Webhook Triggers for real-time response handling.
- **LLM Orchestration:** Integrated with Groq (`llama-3.1-8b-instant`) and Google Gemini Chat Models.
- **Context Awareness:** Maintains conversation state using n8n Memory components.
- **Fail-Safe Routing:** Optimized to handle API concurrency limits and payload structuring.

---

## 🛠️ Tech Stack & Tools
- **Automation Engine:** [n8n](https://n8n.io/)
- **LLM Providers:** Groq API (Llama 3.1), Google Gemini API
- **Communication Platform:** Telegram Bot API
- **Data Exchange Format:** JSON, REST Webhooks

---

## 📐 Workflow Architecture
1. **Telegram Trigger:** Listens for incoming chat messages.
2. **AI Agent Node:** Processes input text and attaches conversation context.
3. **Chat Model Integration:** Sends requests to Groq/Gemini LLMs.
4. **Telegram Send Message:** Delivers the formatted response back to the user.

---

## 🚀 How to Import and Use
1. Clone this repository or download the `My_workflow.json` file.
2. Open your **n8n** instance.
3. Go to **Workflows ➔ Import from File** and select `My_workflow.json`.
4. Configure your credentials:
   - Add your **Telegram Bot Token** (from BotFather).
   - Add your **Groq API Key** or **Gemini API Key**.
5. Toggle the workflow to **Active / Published**.
