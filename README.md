# Barbeque Nation Booking Chatbot Agent

## 📌 Overview

This project implements a conversational AI chatbot for **Barbeque Nation** that supports inbound queries, booking creation, updates, and cancellations for its restaurants in **Delhi** and **Bangalore**. It is built using a state-machine-based architecture, allowing the chatbot to follow structured flows and transition smoothly between conversation stages.

---

## 🚀 Features

- 🔍 **FAQ Handling** – Answers common customer queries using a property-specific knowledge base.
- 🧾 **New Booking** – Takes new reservation requests from customers.
- ♻️ **Booking Update/Cancellation** – Allows users to modify or cancel existing bookings.
- 🧠 **Stateful Conversation Flow** – Maintains and transitions between conversation states for coherence.
- 📚 **Knowledge Base-Driven** – Property-wise structured data retrieval.
- 📈 **Post-Call Analysis (BONUS)** – Analyzes conversation performance and logs unresolved cases.
- 💬 **Custom Chatbot UI (BONUS)** – Hosted frontend chatbot UI built using reverse-engineered API endpoints.

---

## 🛠️ Requirements

- Python 3.11+
- Conda (Miniconda or Anaconda)
- Git
- FastAPI or Flask
- MongoDB (or JSON-based fallback)
- Ngrok (for tunneling to phone interface)
- [RetellAI Platform](https://beta.retellai.com/) access

---
##  Get your Grok api key from   
- https://console.groq.com/home 


##  Run the chatbot
- python main.py