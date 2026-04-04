# FitHub CRM - Fitness Center Management System 🏋️‍♂️

**FitHub CRM** is a comprehensive Salesforce-based solution designed to modernize gym operations. As the Team Lead, I spearheaded the development of this platform to bridge the gap between manual member tracking and automated business intelligence.

---

## 📌 Project Overview
- **Platform:** Salesforce (Lightning Experience)
- **Primary Tools:** Flow Builder, Object Manager, App Builder, Data Import Wizard.
- **Team Lead:** HARISH M (@Harish2859)
- **Core Objective:** To automate membership lifecycle management and provide real-time executive analytics.

---

## 🛠️ Key Technical Features

### 1. Data Architecture & Security
- **Custom Objects:** Engineered 'Trainers' and 'Fitness Classes' objects with specialized relationships.
- **Role-Based Access (RBAC):** Configured the **FitHub Trainer Profile** to ensure data security, restricting access to sensitive financial data while enabling class management.

### 2. Business Logic & Data Integrity
- **Advanced Validation Rules:** Implemented logic to prevent scheduling conflicts (e.g., ensuring Class End Time is always later than Start Time).
- **Custom Picklists:** Standardized 'Membership Status' (Active, Expired, Pending) for clean reporting.

### 3. Process Automation
- **Record-Triggered Flows:** Developed an automated email notification system that triggers the moment a member's status changes to 'Expired', improving retention rates.

### 4. Business Intelligence (BI)
- **Executive Dashboards:** Created a high-level "FitHub Executive Dashboard" featuring Donut Charts for real-time membership breakdown.
- **Custom Reports:** Built grouped reports to track trainer workloads and member engagement.

---

## 🏗️ Project Roadmap & Completion Status

### Phase 1: Requirement Analysis & Planning ✅
- [x] Defined Actor-User roles and business requirements.
- [x] Mapped ERD (Entity Relationship Diagram) to Salesforce Objects.

### Phase 2: Backend Development & Configuration ✅
- [x] Custom Object and Field-level implementation.
- [x] Built core Validation Rules and Picklist logic.

### Phase 3: Automation & UX ✅
- [x] Record-Triggered Flow development.
- [x] Custom App creation (FitHub CRM) and Navigation Tabs.

### Phase 4: Data Migration & Security ✅
- [x] Successfully migrated external member data via **CSV Data Import Wizard**.
- [x] Applied Field-Level Security and Profile permissions.

### Phase 5: Deployment & Documentation ✅
- [x] Deployed the system to multiple users (Giridharan S, Dinesh Karthick S).
- [x] Finalized Technical Documentation and Project Handover.

---

## 👥 The Development Team
- **Harish M** - Team Lead & Lead Developer
- **Giridharan S** - Associate Developer
- **Lokesh M** - Associate Developer
- **Dinesh Karthick S** - Associate Developer

---

Proof Of Work

![WhatsApp Image 2026-04-04 at 6 31 06 PM](https://github.com/user-attachments/assets/0c441297-869f-48a6-b885-30e6f0f8afb0)


## 🚀 Final Conclusion
The FitHub CRM successfully demonstrates the power of cloud-based automation. By reducing manual entry errors by 100% (via validation) and ensuring instant communication (via Flows), the system provides a scalable foundation for any modern fitness center.
