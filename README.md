# 🎓 AI-Powered Student Placement Tracker

## 📌 Project Overview
AI-Powered Student Placement Tracker is a Salesforce CRM project designed to manage and track the complete student placement process from registration to final selection.

This project helps Placement Coordinators monitor student applications, interview rounds, company drives, and hiring status through automation, reports, and dashboards.

---

## 🚀 Features

✅ Student Management

✅ Company Management

✅ Job Drive Tracking

✅ Application Tracking

✅ Interview Round Management

✅ Eligibility Calculation using Formula Fields

✅ Automated Status Updates using Record-Triggered Flows

✅ Validation Rules

✅ Role Hierarchy & Permission Sets

✅ Reports & Dashboards

✅ Security & Sharing Model

---

## 🏗️ Salesforce Admin Concepts Used

- Custom Objects & Fields
- Object Relationships
- Validation Rules
- Formula Fields
- Record-Triggered Flows
- Approval Process
- Reports & Dashboards
- Security Model & Sharing
- Role Hierarchy
- Permission Sets
- Record Types

---

## 📊 Data Model

Student → Application → Interview Round

Company → Job Drive → Application

### Custom Objects

### Student__c
- Name
- Email
- Branch
- CGPA

### Company__c
- Company Name
- Industry
- Package Offered

### Job_Drive__c
- Drive Name
- Eligibility Criteria
- Drive Date

### Application__c
- Student Lookup
- Job Drive Lookup
- Status

### Interview_Round__c
- Application (Master-Detail)
- Round Name
- Result

---

## ⚡ Automation

### Eligibility Formula
```
IF(CGPA__c >= 7, "Eligible", "Not Eligible")
```

### Record Triggered Flow
When Interview Round Result = "Selected"

➡ Application Status automatically updates to "Selected"

---

## 🔒 Security Model

- Organization-Wide Default (OWD) = Private
- Placement Manager Role
- Placement Coordinator Role
- Placement Admin Permission Set
- Placement Interviewer Permission Set

---

## 📈 Reports & Dashboards

- Total Students Registered
- Applications by Status
- Company-wise Placements
- Selected Students Report
- Placement Success Dashboard

---

## 🛠️ Platform

- Salesforce Admin
- Flow Builder
- Reports & Dashboards
- Validation Rules
- Security & Sharing

---

## 👩‍💻 Developed By

**Namrata Gajanan Girhe**

Salesforce Administrator Learner | Final Year ENTC Student

📍 Maharashtra, India

🔗 LinkedIn: www.linkedin.com/in/namrata-girhe-21577a352

🔗 Trailhead: trailhead.salesforce.com

#Salesforce #SalesforceAdmin #CRM #OpenToWork #Freshers
