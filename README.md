# AI Resume Checker Agent

An AI-powered resume evaluation system built using Make.com, Telegram Bot API, Google Docs API, and Gmail API.

The system automates resume analysis by extracting content from a Google Docs resume, generating an AI-based evaluation, and delivering a structured report via email.

---

## 📌 Overview

This project demonstrates a modular automation architecture that integrates messaging platforms, document processing, AI evaluation, and email delivery into a single workflow.

It is designed for students and job seekers who want instant resume feedback through a Telegram interface.

---

## 🧠 System Architecture

```
User (Telegram)
        |
        v
Telegram Watch Updates
        |
        v
AI Orchestrator (Make.com)
        |
        v
Resume Fetch Service (Google Docs API)
        |
        v
AI Evaluation Engine
        |
        v
Gmail Delivery Service
        |
        v
Email Report to User
```

---

## 🚀 Features

- Telegram-based conversational interface  
- Intent-based AI message handling  
- Google Docs resume content extraction  
- Automated AI-driven resume evaluation  
- Structured email report generation  
- Modular service-based automation design  

---

## 🛠 Tech Stack

- **Make.com** – Workflow orchestration  
- **Telegram Bot API** – User interaction layer  
- **Google Docs API** – Resume content extraction  
- **Gmail API** – Email report delivery  
- **AI Agent** – Resume analysis and evaluation  

---

## 📂 Project Structure

```
blueprints/
 ├── 01-telegram-orchestrator.json
 ├── 02-resume-fetch-service.json
 └── 03-email-delivery-service.json
```

---

## ⚙️ Workflow

1. User initiates conversation via Telegram  
2. AI agent identifies user intent  
3. Google Docs resume link is parsed  
4. Resume content is extracted  
5. AI generates evaluation report  
6. Report is sent to the user's email  

---

## 🎯 Use Case

This system is designed to automate resume evaluation for students and job seekers using a messaging-first approach.

---

## 🔮 Future Improvements

- Resume scoring and ranking system  
- ATS compatibility analysis  
- PDF report export  
- Web-based dashboard interface  
- Multi-language support  

---

## 📎 Author

Built as a modular AI automation project demonstrating system integration and workflow design.
