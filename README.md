# Automation Engineer Portfolio

This repository contains a portfolio of AI-powered automation workflows built using **Make (Integromat), OpenAI, Gmail, Google Sheets, Telegram, and Webhooks**.

The goal of these projects is to demonstrate **practical automation systems used in real business workflows**, including AI classification, email automation, chatbot interactions, and AI content generation.

---

# Projects

## 1. AI Lead Qualification System
Automates the classification and prioritization of inbound leads using AI.

**Key features**
- Webhook trigger for incoming leads
- AI classification using OpenAI
- Lead scoring and urgency detection
- Router logic for prioritization
- Structured logging in Google Sheets
- Telegram notification for high-priority leads

**Architecture**

Webhook → OpenAI → Parse JSON → Router → Google Sheets → Telegram

---

## 2. AI Email Auto-Responder
Automatically generates draft replies to incoming emails using AI.

**Key features**
- Gmail inbox monitoring
- AI-generated response drafts
- Gmail draft creation
- Email classification logic
- Labeling of ignored emails

**Architecture**

Gmail → OpenAI → Draft Response → Gmail Draft → Email Labeling

---

## 3. Telegram Chatbot Integration
A chatbot workflow that receives messages and processes them using AI.

**Key features**
- Telegram bot trigger
- AI message processing
- Structured response handling
- Workflow automation through Make

**Architecture**

Telegram → Make Scenario → OpenAI → Telegram Response

---

## 4. AI Content Generator Automation
Generates automated content using AI.

**Key features**
- Automated AI content generation
- Structured output formatting
- Content delivery through Telegram

**Architecture**

Trigger → OpenAI → Format Output → Send to Telegram

---

# Tools Used

- Make (Integromat)
- OpenAI API
- Gmail
- Google Sheets
- Telegram Bot API
- Webhooks

---

# Skills Demonstrated

- AI workflow automation
- Event-driven automation systems
- API integrations
- JSON parsing
- Router logic and conditional flows
- Automated communication workflows
- Business process automation

---

# About Me

I am building practical automation systems focused on **AI-powered workflows and business automation**.

My goal is to design reliable automation pipelines that integrate AI services with real-world tools like email systems, messaging platforms, and databases.

---

# Portfolio Purpose

These projects demonstrate how AI can be integrated into automation platforms to solve real operational problems such as:

- Lead prioritization
- Email response automation
- Conversational workflows
- Automated content generation
