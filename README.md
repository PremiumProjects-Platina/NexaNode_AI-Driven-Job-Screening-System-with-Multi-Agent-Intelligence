# NexaNode_AI-Driven-Job-Screening-System-with-Multi-Agent-Intelligence

# 🧠 AI-Powered Job Screening System 🚀

Welcome to the future of recruitment! This project is built for **Accenture's "Hack the Future: A Gen AI Sprint"** — focused on solving the challenge of **enhancing job screening using AI and data intelligence**.

---

## 📌 Problem Statement
Recruiters spend countless hours manually screening resumes — a process that’s slow, biased, and not scalable. Our goal was to automate this workflow using AI to save time and increase efficiency.

---

## 💡 Our Solution

We built a **multi-agent AI system** that:
- 📝 **Summarizes Job Descriptions** using LLMs
- 📄 **Analyzes Candidate Resumes** and calculates match scores
- ✅ **Shortlists Top Candidates** based on data-driven insights
- ✉️ **Sends Personalized Interview Emails** via a single-click UI

All of this is supported by:
- ⚙️ **Ollama-based local LLMs**
- 🧠 **Custom multi-agent framework**
- 🗃️ **SQLite for long-term memory**
- 🌐 **Flask web interface** for recruiter interaction

---

## 🖥️ Features

- 🔍 Auto JD analysis & key skill extraction  
- 🤖 Resume scoring with AI agents  
- 📊 Match visualization and shortlisting  
- 📬 Email integration with optional test links  
- 💼 Professional UI for recruiters

---

## 🛠️ Tech Stack

| Tool        | Purpose                      |
|-------------|------------------------------|
| 🧠 Ollama    | On-prem LLM inference        |
| 🐍 Python    | Core logic and agents        |
| 🧬 SQLite    | Lightweight memory store     |
| 🌐 Flask     | Web framework & routing      |
| 💌 smtplib   | Email functionality          |
| 🎨 HTML/CSS  | Frontend styling             |

---

## 📸 Screenshots

![UI Screenshot](assets/ui.png)  
*One-click interview invites with candidate details*

---

## 📂 Folder Structure

## ✨ Team
Made with ❤️ by Tinish Uge
Data & AI | Accenture: Hack for the Future A Gen AI Sprint Powered by Data 2025 🚀

```bash
├── agents/
│   ├── jd_summarizer.py
│   ├── resume_matcher.py
│   └── shortlisting_agent.py
├── database/
│   └── job_screening.db
├── templates/
│   └── shortlisted.html
├── send_email.py
├── app.py
├── .env
└── README.md


