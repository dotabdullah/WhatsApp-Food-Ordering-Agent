# 🍴 Food Ordering WhatsApp Automated Agent  

An intelligent **WhatsApp Food Ordering System** built with **n8n** that automates order management, inventory checks, and customer interactions — all through WhatsApp.  

This project is designed to help restaurants and food businesses manage customer interactions efficiently using **AI**, **Google Sheets**, and the **WhatsApp Business Cloud API**.  

---

## 🚀 Project Overview  

The **Food Ordering WhatsApp Automated Agent** allows customers to:  
- 🛍️ Place food orders directly through WhatsApp  
- 📦 Check available items and stock  
- 💬 Ask FAQs and get instant replies  
- 📊 Automatically update orders and inventory in Google Sheets  

All interactions are handled by an AI agent, ensuring customers receive fast, friendly, and professional responses 24/7.  

---

## ⚙️ Tech Stack  

| Component | Description |
|------------|-------------|
| **n8n** | No-code automation platform used to build the workflow |
| **WhatsApp Business Cloud API** | Enables sending and receiving WhatsApp messages |
| **Google Gemini Chat** | AI agent that processes customer queries |
| **Google Sheets** | Manages orders, inventory, and FAQs |
| **Simple Memory Node** | Stores conversation context for better AI replies |

---

## 🧩 Workflow Structure  

1. **WhatsApp Trigger Node** – Captures incoming messages from customers.  
2. **AI Agent Node (Google Gemini Chat)** – Understands customer intent and responds intelligently.  
3. **Simple Memory Node** – Maintains conversation context.  
4. **Google Sheets Node** – Handles:  
   - Orders Sheet 🧾  
   - Inventory Sheet 📦  
   - FAQ Sheet ❓  
5. **WhatsApp Message Node** – Sends automated replies back to customers.  

---

## 💡 Features  

✅ AI-powered natural conversation  
✅ Real-time order & stock management  
✅ Multi-language support (English, Urdu, Hindi, Roman Urdu)  
✅ 24/7 automated responses  
✅ Integration with Google Sheets for dynamic data handling  
✅ Fully customizable workflow inside n8n  

---

## 🧠 How It Works  

1. A customer sends a message to your WhatsApp Business number.  
2. The **Webhook Node** in n8n captures the message.  
3. The **AI Agent** determines intent (Order, FAQ, or Stock Check).  
4. Data is fetched or updated in Google Sheets.  
5. The **HTTP Request Node** sends a WhatsApp response through the **Business Cloud API**.  

---

## 🧰 Setup Guide  

Import the n8n workflow JSON file into your instance.

Configure your credentials:
WhatsApp Access Token
Phone Number ID
Google Sheets Credentials

Activate the workflow and test by sending a WhatsApp message to your business number.

🔐 Environment Variables
Variable	Description
WHATSAPP_ACCESS_TOKEN	Permanent access token from Meta
WHATSAPP_PHONE_NUMBER_ID	Phone number ID from WhatsApp Cloud API
GOOGLE_SHEET_ID	Google Sheet ID containing orders, inventory, and FAQs

🖼️ Example Welcome Message

Welcome to Delicious Restaurant! 🍴  

How can I help you today?  
- Place an Order  
- FAQ  
- Check Items / Stock  

---

📞 Contact

- Developer: Abdullah Shahzad
- 📧 Email: support@xpertswp.com
- 📧 Email: shahzadabdullah37@gmail.com
- 🌐 Website: https://xpertswp.com

💡 If you need a custom automation system for your business — Let’s collaborate!

⭐ Don’t forget to star this repo if you find it helpful!

