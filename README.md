J.A.R.V.I.S – AI Voice Agent for IronFit Fitness Center

An end-to-end automated AI voice assistant built using n8n, ElevenLabs, Google Gemini, and Lovable.
J.A.R.V.I.S can speak in multiple languages, answer gym-related questions, book appointments, send email confirmations, update Google Calendar, and manage data directly from Google Sheets.

## 🎥 Demo Video
Watch the full demo of J.A.R.V.I.S:

[▶️ Watch on YouTube](https://youtu.be/fR3RrUciHIk)


🚀 Project Overview

J.A.R.V.I.S is a fully automated AI agent designed to enhance customer engagement for fitness centers and service-based businesses.
This system allows customers to interact via voice, get information instantly, and complete tasks such as:

Booking gym plans or classes

Getting trainer & service details

Receiving email confirmations

Automatic Google Calendar scheduling

24/7 voice support without human staff

The knowledge base is powered by RAG (Retrieval-Augmented Generation) using structured Google Sheets.

📌 Features

✔ Multilingual Voice Agent (ElevenLabs)

Responds naturally in multiple languages with human-like voice.

✔ RAG-Based Knowledge System

AI pulls real-time information from Google Sheets (gym plans, classes, trainers, hours, pricing, FAQs).

✔ Automated Email System

Sends HTML confirmation emails automatically through Gmail API.

✔ Google Calendar Integration\


Books appointments, checks availability, and manages schedule automatically.

✔ n8n Automation Workflow

Manages entire AI logic, tools, actions, memory, and error handling.
Lovable Website
      ↓
Voice Agent (ElevenLabs)
      ↓
Webhook → n8n Workflow → Google Gemini (LLM)
      ↓
Google Sheets (Knowledge Base)
      ↓
Tools: Gmail + Google Calendar
      ↓
User Output (Voice Response + Email + Booking)

