# hackathon-proposals
# 🏦 Multilingual AI Loan Assistant

A hackathon project proposal for an AI-powered chatbot that assists users in **loan eligibility checks**, **financial guidance**, and **loan applications** via **WhatsApp**.

## 🚀 Key Features
- **Multilingual AI**: Uses **Sarvam.ai** for translation.
- **Loan Eligibility**: NLP-powered intent detection (DistilBERT) with rule-based/API assessment.
- **Alternative Credit Scoring**: Analyzes transaction patterns for users without credit scores.
- **Secure & Scalable**: End-to-end encryption (E2EE), WebSockets for real-time updates, and Kafka for async processing.
- **Loan Matching & Assistance**: Personalized loan suggestions and guidance on documentation.

## 🤖 Workflow Overview
1️⃣ User starts chat & selects language.
2️⃣ NLP extracts intent (eligibility, guidance, financial insights).
3️⃣ Data fetched via input, APIs, or Account Aggregator (AA).
4️⃣ Computes credit score & loan eligibility.
5️⃣ Suggests loan options & next steps.

## 🛠️ Proposed Tech Stack
- **Frontend**: React.js + Next.js, WhatsApp UI (via Twilio API).
- **Backend**: Express.js, WebSockets, Kafka, DistilBERT, Sarvam.ai.
- **Security**: Firebase (encrypted storage), E2EE chat security.

📌 *This is a hackathon project proposal and has not been implemented yet.*
