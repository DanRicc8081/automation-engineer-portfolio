# 🤖 AI Telegram Chatbot for Workflow Automation (Intent-Based Routing)

## 🎥 Demo Video

Short walkthrough of the system and how it works:





## 🧩 Problem

Businesses often lack simple, real-time interfaces to interact with automation systems.

While backend workflows can process data efficiently, triggering or interacting with them typically requires dashboards, APIs, or manual input.

Messaging platforms like Telegram provide a more accessible interface for users to send requests, retrieve information, and trigger automated workflows in real time.



## 💡 Solution

This project integrates a Telegram chatbot with a Make automation workflow.

When a user sends a message to the Telegram bot, the system receives the message, processes it using OpenAI, and generates an appropriate response.

The response is then sent back to the user through Telegram, creating a seamless conversational experience.

This system acts as a conversational interface for triggering and interacting with automation workflows in real time.



## 🏗️ Architecture

Telegram Message → Webhook (Make) → OpenAI Processing → Response Generation → Telegram Bot Response

This modular architecture allows the chatbot to be extended with routing logic, database integrations, or workflow triggers.



## 🛠️ Tech Stack

- Make (Integromat)
- Telegram Bot API
- OpenAI API

This stack enables scalable and modular automation workflows using no-code/low-code tools combined with AI services.



## 🚀 Key Features

- Real-time message processing via Telegram Bot API  
- AI-powered response generation using OpenAI  
- Conversational interface for triggering automation workflows  
- Modular architecture for integrating external systems  
- Scalable design for adding routing logic and commands  



## 📈 Outcome

This system demonstrates how messaging platforms can be transformed into powerful interfaces for automation systems.

It enables real-time interaction with workflows, reducing friction between users and backend automation while providing a scalable foundation for conversational applications.



## 🔮 Possible Improvements

- Adding conversation memory for context-aware interactions  
- Implementing command-based routing (/start, /status, etc.)  
- Integrating with databases or internal tools  
- Connecting chatbot actions to business workflows (CRM, APIs)  



## 📸 Screenshots

### Automation Architecture
![Architecture](screenshots/telegram-chatbot-architecture.png)

### Workflow Logic (Make Scenario)
![Workflow](screenshots/telegram-chatbot-workflow.png)

### Example Interaction
![Chatbot](screenshots/telegram-chatbot-response.png)
