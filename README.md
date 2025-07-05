# 🤖 AI-Sahayak – Your Smart Compliance Partner for Indian SMEs 🇮🇳

![AI-Sahayak Banner](./assets/banner.png)

**AI-Sahayak** is a multilingual, mobile-first AI-powered compliance assistant built to simplify regulatory compliance for India’s 63M+ small and medium enterprises (SMEs). It provides real-time alerts, document scanning, multilingual summaries, and expert guidance to help SMEs stay legally compliant — easily, affordably, and confidently.

---

## 📌 Problem

Most Indian SMEs struggle with legal compliance due to:
- Over 1,500 laws and 69,000+ compliance rules
- High penalties (₹5,000+ for simple delays)
- Legalese-heavy updates in English
- Lack of accessible, timely guidance

Compliance shouldn’t be a luxury for big firms. AI-Sahayak is **Built for Bharat** — tier-2/3 cities, regional languages, mobile-first, and accessible.

---

## 🚀 Solution

AI-Sahayak empowers SMEs with:

- ✅ Real-time compliance alerts (GST, PF, ESIC, etc.)
- ✅ Multilingual summaries (Hindi, Telugu, etc.)
- ✅ Document scanning + risk flagging
- ✅ WhatsApp/SMS/email reminders
- ✅ Smart checklists + auto-filing support
- ✅ CA/CS booking within platform
- ✅ Continual AI learning from user feedback

---

## 🖼️ UI Mockups

Here are some design mockups built with Figma:

### 🏠 Dashboard

![Dashboard UI](./assets/ui-dashboard.png)

### 📅 Compliance Calendar

![Calendar UI](./assets/ui-calendar.png)

### ⚠️ Smart Alerts

![Alerts UI](./assets/ui-alerts.png)

### 📄 Document Scanner

![Scanner UI](./assets/ui-scanner.png)

### 🧠 Chatbot (Hindi/English)

![Chatbot UI](./assets/ui-chatbot.png)

### 📞 Expert Consultation

![Consult Booking UI](./assets/ui-expert-booking.png)

---

## 🧩 Core Features

| Feature                     | Description                                                              |
|----------------------------|--------------------------------------------------------------------------|
| 📅 Compliance Calendar     | Track upcoming deadlines with urgency indicators                         |
| 🔔 Smart Alerts            | Personalized alerts via WhatsApp/SMS/Email                               |
| 📄 Document Scanner        | Upload GST returns, invoices, etc. — get flagged risks & missing info    |
| 🧠 Auto-filing Assist      | Guided help for filing returns, forms                                    |
| 📁 Document Repository     | Cloud-based storage for all your compliance docs                         |
| 🗣️ Multilingual Chatbot    | Ask compliance questions in Hindi, Telugu, etc.                          |
| 🎯 CA/CS Expert Booking    | Book verified consultants from inside the app                            |
| 🧠 Continual AI Learning   | Feedback loop updates models for better accuracy                         |

---

## 🏗️ Tech Stack

| Layer              | Tools / Frameworks                                           |
|-------------------|--------------------------------------------------------------|
| **Frontend**       | React.js, Tailwind CSS, Figma (UI/UX Design), Flutter (mobile) |
| **Backend**        | Node.js, FastAPI (Python), Express.js                        |
| **AI/NLP Engine**  | LangChain, OpenAI API, HuggingFace Transformers, spaCy, RAG |
| **OCR**            | Tesseract + Whisper (audio/text parsing if needed)          |
| **Database**       | MongoDB, PostgreSQL                                          |
| **Cloud & Infra**  | AWS Lambda, S3, RDS, Firebase                                |
| **Messaging APIs** | WhatsApp Business API, Twilio, Email/SMS Gateways           |

---

## 🧠 Architecture Overview

                ┌────────────────────────────┐
                │      Government Portals    │
                │ (GSTN, MCA, EPFO, ESIC...) │
                └────────────┬───────────────┘
                             │
               ┌────────────▼────────────┐
               │         ETL Layer       │
               │  - Web Scrapers & APIs  │
               │  - Data Cleansing       │
               └────────────┬────────────┘
                             │
        ┌────────────────────▼────────────────────┐
        │             AI/NLP Engine               │
        │ - Named Entity Recognition (NER)        │
        │ - Rule Extraction & Summarization       │
        │ - State/Sector Classification           │
        └────────────────────┬────────────────────┘
                             │
                ┌────────────▼────────────┐
                │   Compliance Validator  │
                │  - Risk Assessment      │
                │  - Rule Mapping         │
                └────────────┬────────────┘
                             │
                ┌────────────▼────────────┐
                │     Smart Alerts Engine │
                │  - WhatsApp / SMS / Email │
                │  - Calendar To-Dos       │
                └────────────┬────────────┘
                             │
                ┌────────────▼────────────┐
                │     User Interface      │
                │  - Mobile Dashboard     │
                │  - Hindi/Telugu Chatbot │
                └─────────────────────────┘
                             │
       ┌────────────────────▼────────────────────┐
       │      User Feedback & Model Tuning       │
       │  - Thumbs up/down on summaries          │
       │  - AI retraining loop (continuous)       │
       └─────────────────────────────────────────┘

                 ┌──────────────┐
                 │     OCR      │◄──────User-Uploaded Docs (PDF, invoices)
                 └────┬─────────┘
                      ▼
             ┌──────────────┐
             │ Risk Scanner │
             └──────────────┘


- Government Portals: GSTN, MCA, EPFO, ESIC
- User-uploaded docs: Contracts, invoices, returns
- AI: Summarization, NER, Rule Extraction
- Delivery: Mobile UI + WhatsApp/SMS/email

---

## 🧪 Status

- ✅ Completed: Pitch Deck + UI + Architecture
- ✅ Shortlisted: AI Idea Challenge 2025 – Final Jury Round
- 🚧 In Progress: MVP (backend integration, WhatsApp API setup)

---

## 🧑‍💻 Author

**Rohit Nunnaguppala**  
Final-year CSE @ Amrita Vishwa Vidyapeetham  
📧 nunnaguppalarohit@gmail.com  
🔗 [LinkedIn](https://linkedin.com/in/rohit-nunnaguppala)

---

## 🤝 Contributing

Want to improve the backend/API setup, suggest better UI, or help with multilingual NLP?
Feel free to fork and submit a PR.

---

## 📄 License

This project is licensed under the MIT License.

---

> "Running a business shouldn’t feel like walking blindfolded."  
> Let’s empower small businesses with clarity, compliance, and confidence — in their own language.

