# AI Lead Qualification System

## 🎥 Demo Video

Short walkthrough of the system and how it works:

[▶️ Watch Demo Video](https://www.loom.com/share/4f232efe06224b9abc1340f28c3114aa) 

## Problem

Businesses often receive many inbound leads through forms, chat systems, or APIs.  
Reviewing and prioritizing each lead manually can be slow and inefficient, especially when only a small portion of leads require immediate attention.

---

## Solution

This automation uses **AI classification and workflow routing** to automatically evaluate inbound leads.

When a lead arrives through a webhook, the system sends the message to **OpenAI** for analysis.  
The AI classifies the lead's **intent, urgency, and lead score**, and the workflow routes the lead to the appropriate path.

All leads are stored in **Google Sheets**, while **high-priority leads trigger an instant Telegram alert**.

---

## Architecture
Webhook → OpenAI → Parse JSON → Router → Google Sheets → Telegram

---

## Tools Used

- Make (Integromat)
- OpenAI API
- Google Sheets
- Telegram Bot
- Webhooks

---

## Key Logic

The automation evaluates leads using a scoring system:

**High Priority Lead**
- lead_score ≥ 70  
OR  
- urgency = high  

➡ Logged in Google Sheets  
➡ Telegram alert sent immediately

---

**Normal Lead**

- lead_score between 40–69  
- urgency not high  

➡ Logged in Google Sheets

---

**Low Priority Lead**

- lead_score < 40  

➡ Logged in Google Sheets for record keeping

---

## Outcome

This system automatically prioritizes inbound leads and ensures that only **high-value leads trigger immediate notifications**, reducing manual review time and improving response speed.

---

## Possible Improvements

In a production environment, Google Sheets could be replaced with:

- CRM systems (HubSpot, Salesforce)
- Databases (PostgreSQL, Airtable)
- Lead management platforms

## Screenshots

### Automation Architecture
![Architecture](screenshots/lead-qualification-automation-architecture.png)

### Router Logic
![Router](screenshots/lead-qualification-router-logic.png)

### Example Output
![Output](screenshots/lead-qualification-output-google-sheets.png)
