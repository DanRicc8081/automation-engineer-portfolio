# 🤖 AI Telegram Chatbot with Intent Routing

## 🎥 Demo Video

Short walkthrough of the system and how it works:

👉 [▶️ Watch Demo Video](https://www.loom.com/share/42a9d0174df54f97813f2abae811ca06)

## 🧩 Problem

Businesses and automation systems often need a simple way to interact with workflows in real time.

Messaging platforms like Telegram can be used as an easy interface to send requests, receive answers, and trigger automated processes.

## 💡 Solution

This project connects a Telegram chatbot with a Make automation workflow.

When a user sends a message, the workflow receives the message, processes it with OpenAI, and returns an appropriate response through Telegram.

The system can route different types of messages depending on the detected intent.

## 🧱 Architecture

Telegram Message → Make → OpenAI → JSON Parsing → Google Sheets → Router → Telegram Response

This workflow processes incoming Telegram messages, classifies the user intent using AI, logs the interaction, and routes the response based on the result.

## 🛠️ Tech Stack

- Make (Integromat)
- Telegram Bot API
- OpenAI API
- Google Sheets
- JSON Parser

## 🚀 Key Features

- Real-time Telegram message processing  
- AI-powered intent detection  
- Structured JSON parsing  
- Intent-based routing  
- Google Sheets logging  
- Automated Telegram responses  

## 📈 Outcome

This project demonstrates how messaging platforms can be used as conversational interfaces for automation workflows.

It enables real-time user interaction and provides a foundation for chatbot-based workflow automation.

## 🔮 Possible Improvements

- Add conversation memory  
- Add command-based routing such as /start or /help  
- Connect the chatbot to databases or CRM tools  
- Expand routing for more user intents  

## 📸 Screenshots

### Automation Architecture
![Architecture](screenshots/telegram-chatbot-architecture.png)

### Router Logic
![Router](screenshots/telegram-chatbot-router.png)

### Example Output
![Output](screenshots/telegram-chatbot-output.png)
