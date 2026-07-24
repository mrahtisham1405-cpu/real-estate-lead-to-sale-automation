<div align="center">

# 🏡 Real Estate Lead-to-Sale CRM Automation

### Production-Ready n8n Workflow for Real Estate Agencies

Capture Leads • Detect Duplicates • Score Leads • Assign Agents • Manage CRM • Send Notifications

![n8n](https://img.shields.io/badge/n8n-Workflow%20Automation-orange)
![Google Sheets](https://img.shields.io/badge/Google%20Sheets-CRM-green)
![Gmail](https://img.shields.io/badge/Gmail-Notifications-red)
![JavaScript](https://img.shields.io/badge/JavaScript-Data%20Processing-yellow)
![Status](https://img.shields.io/badge/Project-Production%20Ready-success)

</div>

---

# 📖 Overview

This project is a production-ready Real Estate CRM Automation built using **n8n**.

It automates the complete lead management process from inquiry submission to CRM updates, duplicate detection, lead scoring, agent assignment, notifications, and error handling.

Instead of manually checking emails, spreadsheets, and duplicate inquiries, the entire process runs automatically.

---

# 🚀 Key Features

## 🌐 Lead Capture

- Website Form Integration
- Webhook Trigger
- Real-time Processing

---

## 🧹 Data Processing

- Phone Number Formatting
- Email Normalization
- Input Validation
- Data Standardization

---

## 🧠 Smart CRM Logic

- Unique Lead ID Generation
- Lead Score Calculation
- Lead Priority
- Automatic Agent Assignment
- Duplicate Lead Detection
- Inquiry Counter
- Activity Log

---

## 📊 CRM Management

- Google Sheets CRM
- Automatic Record Creation
- Automatic Record Updates
- Lead Status Tracking

---

## 📧 Notifications

- New Lead Email
- Duplicate Lead Email
- Error Notification Email

---

## 🛡 Reliability

- Error Trigger Workflow
- Automation Logs
- Centralized Error Monitoring

---

# 🏗 System Architecture

```text
                    Website Form
                          │
                          ▼
                  n8n Webhook Trigger
                          │
                          ▼
               Clean & Standardize Data
                          │
                          ▼
                 Process Lead Information
                          │
                          ▼
                Validate Required Fields
                          │
                          ▼
               Check Existing Customer
                          │
                ┌─────────┴─────────┐
                │                   │
           New Lead          Existing Lead
                │                   │
         Append New Row       Update Existing Row
                │                   │
                └─────────┬─────────┘
                          ▼
                 Google Sheets CRM
                          │
                          ▼
                 Email Notification
                          │
                          ▼
                  Automation Logs
```

---

# 📂 Workflow Structure

```
Webhook
│
├── Clean Input Data
│
├── Process Lead Data
│      ├── Lead Score
│      ├── Lead Priority
│      ├── Assigned Agent
│      ├── Inquiry Count
│      └── Activity Log
│
├── Validate Lead
│
├── Check Existing Lead
│
├── Duplicate Lead?
│      │
│      ├── New Lead
│      │      ├── Generate Lead ID
│      │      ├── Save to CRM
│      │      └── Send Email
│      │
│      └── Existing Lead
│             ├── Update CRM
│             ├── Increment Inquiry Count
│             └── Send Duplicate Email
│
└── Error Handling Workflow
```

---

# 📊 CRM Database Structure

| Field | Description |
|---------|------------|
| Lead ID | Unique Lead Identifier |
| Full Name | Customer Name |
| Phone | Customer Phone |
| Email | Customer Email |
| Property Interest | House / Plot / Commercial |
| Preferred Location | Customer Preferred Area |
| Budget | Buying Budget |
| Lead Score | High / Medium / Low |
| Lead Priority | 1 / 2 / 3 |
| Assigned Agent | Sales Representative |
| Inquiry Count | Number of Inquiries |
| Status | Lead Status |
| Activity Log | Customer History |
| Notes | Internal Notes |
| Created At | Creation Time |
| Updated At | Last Update |

---

# 💼 Business Benefits

✅ No Lost Leads

✅ Automatic Duplicate Detection

✅ Faster Lead Response

✅ Centralized CRM

✅ Better Sales Management

✅ Lead Prioritization

✅ Reduced Manual Work

✅ Complete Customer History

---

# 🛠 Technology Stack

| Technology | Usage |
|------------|------|
| n8n | Workflow Automation |
| Google Sheets | CRM Database |
| Gmail | Email Notifications |
| JavaScript | Business Logic |
| Webhooks | Lead Capture |
| Lovable | Website Frontend |

---

# 📷 Project Screenshots

```
01_lovable.png

02_lead.png

03_error handle.png

04_excel crm.png

05_excel error handle.png

06_gmail.png

```

---

# 📈 Workflow Capabilities

✔ Website Lead Capture

✔ Data Cleaning

✔ Lead Validation

✔ Lead Scoring

✔ Agent Assignment

✔ Duplicate Detection

✔ CRM Management

✔ Email Automation

✔ Error Handling

✔ Automation Logs

---

# 🔒 Error Handling

A dedicated Error Workflow automatically:

- Captures execution failures
- Sends error notification emails
- Logs workflow errors
- Simplifies troubleshooting

---

# 🚀 Future Roadmap

- Facebook Lead Ads Integration
- WhatsApp Business Integration
- Google Calendar Booking
- Property Viewing Scheduler
- AI Lead Qualification
- Google Docs Agreement Generation
- PDF Automation
- Reporting Dashboard
- Zameen.com Integration
- OLX Integration

---

# ⚙ Installation

1. Import the workflow into n8n.
2. Configure Google credentials.
3. Connect Google Sheets.
4. Connect Gmail.
5. Update Webhook URL.
6. Activate the workflow.
7. Test using sample inquiries.

---

---

# 📄 License

MIT License

---

# 👨‍💻 Author

**Ahtisham Jalil**

AI Automation Developer

Specializing in:

- n8n Automation
- AI Agents
- CRM Automation
- Workflow Design
- Business Process Automation

---

<div align="center">

### ⭐ If you found this project useful, please consider giving it a star.

</div>
