# 🚗 AI SDR for Automotive Industry using Make.com + OpenAI + Google Sheets

An end-to-end AI-powered Sales Development Representative (AI SDR) workflow for the Automotive industry built using **Make.com**, **OpenAI GPT**, and **Google Sheets CRM**.

This project demonstrates how to automate customer qualification, lead capture, CRM updates, and AI-driven conversations without writing custom backend code.

---

# 📌 Project Overview

The AI SDR engages prospective customers through an intelligent chat experience and automatically:

- Collects customer information
- Qualifies sales leads
- Understands vehicle requirements
- Updates CRM automatically
- Generates conversation summaries
- Prevents duplicate questions
- Maintains conversation context throughout the interaction

This project is designed for dealerships, automotive retailers, AI consultants, and automation developers.

---

# 🏗 Architecture

Customer
      │
      ▼
 AI Chat Interface
      │
      ▼
    Make.com
      │
      ├────────► OpenAI GPT
      │
      ├────────► Google Sheets CRM
      │
      └────────► Lead Qualification Engine

---

# ✨ Features

✅ AI-powered Automotive Sales Assistant

✅ Customer Qualification

✅ BANT Qualification

- Budget
- Authority
- Need
- Timeline

✅ Collects

- First Name
- Last Name
- Email
- Mobile Number

✅ Vehicle Information

- New / Used
- Purchase / Lease
- Make
- Model
- Year

✅ CRM Automation

- Create New Lead
- Update Existing Lead
- Prevent Duplicate Records

✅ Context-aware Conversations

The AI remembers previous answers and never asks the same question twice.

✅ Conversation Summary

Automatically generates customer interaction summary.

---

# 📂 Repository Structure

```
01_AI SDR - FUNCTIONAL PROCESS.pdf
```

High-level functional flow of the AI SDR.

---

```
02_AI SDR - Setup Requirement Checklist.pdf
```

Prerequisites required before implementing the solution.

Includes

- OpenAI
- Make.com
- Google Sheets
- API Keys
- CRM Setup

---

```
03_MAKE_DOT_COM_WIRING.pdf
```

Complete Make.com module wiring.

Shows

- Routers
- Filters
- Variables
- OpenAI Modules
- Google Sheets Modules

---

```
04_SYSTEM_USER_PROMPT.pdf
```

Production-ready prompts.

Contains

- System Prompt
- User Prompt
- Prompt Engineering
- Conversation Logic
- Guard Rails

---

```
05_MAKE_DOT_COM_WORKFLOW_SCREENSHOT.pdf
```

Workflow screenshots of the complete Make.com automation.

---

```
06_SampleCarPriceDataset.csv
```

Sample automotive dataset used by the AI assistant.

Contains

- Vehicle Make
- Model
- Year
- Price
- Fuel Type
- Engine
- Transmission
- Vehicle Specifications

---

# 🧠 AI Conversation Flow

```text
Customer Starts Chat
        │
        ▼
Collect Customer Information

First Name
Last Name
Email
Phone

        │
        ▼
Vehicle Qualification

New or Used?

        │
        ▼
Purchase or Lease?

        │
        ▼
Preferred Make

        │
        ▼
Preferred Model

        │
        ▼
Budget

        │
        ▼
Timeline

        │
        ▼
Need

        │
        ▼
Authority

        │
        ▼
Generate Summary

        │
        ▼
Update CRM
```

---

# 🛠 Technologies Used

- OpenAI GPT
- Make.com
- Google Sheets
- Prompt Engineering
- AI Sales Automation
- Workflow Automation
- CRM Automation

---

# 📊 CRM Fields

The AI automatically updates:

| Field | Description |
|--------|-------------|
| First Name | Customer First Name |
| Last Name | Customer Last Name |
| Email | Email Address |
| Mobile | Phone Number |
| Vehicle Type | New / Used |
| Purchase Type | Purchase / Lease |
| Make | Vehicle Make |
| Model | Vehicle Model |
| Year | Preferred Year |
| Budget | Customer Budget |
| Need | Customer Need |
| Authority | Decision Maker |
| Timeline | Purchase Timeline |
| Lead Stage | Qualified / Unqualified |
| Conversation Summary | AI Generated Summary |

---

# 🚀 Workflow Highlights

✔ Intelligent lead qualification

✔ AI remembers previous answers

✔ No repeated questions

✔ CRM auto-update

✔ Modular Make.com workflow

✔ Easy customization

✔ Production-ready prompt engineering

---

# 💡 Business Benefits

- Reduce manual lead qualification
- Improve response time
- Automate CRM updates
- Increase sales productivity
- Better customer engagement
- Consistent customer experience
- 24×7 AI Sales Representative

---

# 🎯 Ideal Use Cases

- Automotive Dealerships
- Used Car Dealers
- EV Dealers
- Vehicle Leasing Companies
- Fleet Sales
- Automotive Consultants
- AI Automation Agencies

---

# 🔮 Future Enhancements

- Live Dealer Inventory
- Vehicle Recommendation Engine
- Appointment Scheduling
- Test Drive Booking
- WhatsApp Integration
- Email Automation
- Voice AI
- Multi-language Support

---

# 🤝 Contributing

Contributions are welcome.

Feel free to submit:
- Improvements
- Bug Fixes
- Workflow Enhancements
- Prompt Engineering Updates
- Additional Vehicle Datasets

---

# ⭐ Support

If you find this project useful,
please consider giving it a ⭐ on GitHub.

---

# 📄 License
This project is intended for educational and demonstration purposes.
Feel free to modify and adapt it for your own implementations.

---

## 👤 Author
**Nagarajan Lakshmanan**
AI Automation | Enterprise AI | Make.com | OpenAI | AI Agents | Workflow Automation
