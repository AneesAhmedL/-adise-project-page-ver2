# ADISE: Advanced Multi-Tier AI Assistant

![ADISE Banner](https://img.shields.io/badge/AI%20Assistant-ADISE-blue?style=for-the-badge)
![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=flat-square&logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-lightgrey?style=flat-square&logo=flask)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=flat-square&logo=mongodb)

**ADISE** is a production-ready, highly secure AI assistant built to deliver reliable, context-aware conversational experiences. Designed with enterprise-grade security and robust reliability in mind, ADISE features an advanced multi-tier AI failover mechanism to ensure uninterrupted service.

🌐 **Live Website:** [Explore ADISE Live](https://adise-ai-assistant-ver2.onrender.com/)

---

## 🚀 Key Features

* **Multi-Tier AI Failover Architecture:** Automatically routes requests through primary and secondary Google Gemini models. If primary endpoints experience rate limits or heavy traffic, it seamlessly falls back to Meta Llama via Hugging Face routing.
* **Google Search Grounding:** Integrates real-time web search grounding to provide accurate, up-to-date answers for dynamic queries.
* **Secure Authentication & OTP:** Complete user authentication workflow featuring secure password hashing (Werkzeug) and email-based OTP verification via Brevo.
* **Session Management:** Secure, encrypted HTTP-only session cookies with strict Samesite policies to prevent CSRF and session hijacking.
* **Custom Admin Dashboard:** Includes a protected, hidden administrative portal for monitoring system data, user statistics, and chat threads with accurate IST timestamping.

---

## 🛠️ Tech Stack

* **Backend:** Python, Flask
* **Database:** MongoDB (with secure TLS/SSL configuration via PyMongo)
* **AI Providers:** Google GenAI SDK (Gemini Flash models), Hugging Face Router (Llama-3.1-8B-Instruct)
* **Security:** Werkzeug Security, python-dotenv, Brevo SMTP API

---

## 📊 System Architecture Overview

---

## 🔒 Security & Privacy Notice
*This public repository serves as a technical showcase and documentation hub. Core proprietary backend logic, database configurations, and environment credentials are kept in secure private repositories.*
