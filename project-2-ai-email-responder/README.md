# 📧 AI Email Auto-Responder System

## 🎥 Demo Video

Short walkthrough of the system and how it works:

👉 [▶️ Watch Demo Video](https://www.loom.com/share/8ac0332bd36f4fc99840d3a1fa38a016))

## 🧩 Problem

Businesses receive a large volume of emails, many of which are repetitive or low-priority.  
Manually reviewing, categorizing, and responding to each message can be time-consuming and inefficient.

## 💡 Solution

This automation uses **AI-powered classification and response generation** to streamline email handling.

When a new email arrives in Gmail, the system extracts the content and sends it to OpenAI for analysis.  
The AI classifies the message and generates a suggested response.

The response is parsed into structured data, and a router determines whether a reply should be created or the email should be ignored.

If a response is required, a draft is automatically created in Gmail.  
If not, the email is labeled as ignored for reference.

## 🧱 Architecture

Gmail Trigger → Extract Email → OpenAI → JSON Parsing → Router → Gmail Draft / Label

This workflow processes incoming emails, classifies them using AI, and routes them based on intent in real time.

## 🛠 Tech Stack

- Make (Integromat)  
- OpenAI API (GPT)  
- Gmail API  
- Webhooks  

## 🚀 Key Features

- Automatic email classification using AI  
- AI-generated contextual responses  
- Conditional routing (reply vs ignore)  
- Draft email creation for human review  
- Automatic labeling for ignored emails  

## 📈 Outcome

This system automates email triage and response generation, reducing manual workload while ensuring human control over outgoing communication.

## 🔮 Possible Improvements

In a production environment, this system could be extended by:

- Integrating with CRM systems (HubSpot, Salesforce)  
- Adding sentiment analysis for better prioritization  
- Auto-sending responses for low-risk scenarios  
- Storing conversations in a database (PostgreSQL, Airtable)  
- Building analytics dashboards for email trends  

## 📸 Screenshots

### Automation Architecture
![Architecture](screenshots/email-responder-automation-architecture.png)

### Router Logic
![Router](screenshots/email-responder-router-logic.png)

### Example Output (Gmail Draft)
![Output](screenshots/email-responder-gmail-draft.png)
