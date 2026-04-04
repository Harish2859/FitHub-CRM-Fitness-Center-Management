# FitHub CRM - Fitness Center Management 🏋️‍♂️

**FitHub CRM** is a Salesforce-based solution designed to streamline operations and enhance member experiences for fitness centers. This project leverages Salesforce's core capabilities to integrate membership tracking, trainer allocation, and automated notifications.

---

## 📌 Project Overview
- **Platform:** Salesforce (Apex, LWC, Flows)
- **Sector:** Healthcare / Fitness
- **Team Lead:** HARISH M (@Harish2859)
- **Status:** Phase 2 (Backend Development & Configuration) - STARTED 🚀

## 🛠️ Key Features
- **Membership Management:** Track active subscriptions and renewals.
- **Dynamic Scheduling:** Assign trainers to classes based on specialization.
- **Automated Alerts:** Personalized notifications for subscription expiry.
- **Data Analytics:** Robust reporting for operational growth.

## 🏗️ Data Model (Completed Schema)
The following objects and relationships have been established:
1. **Members (Contact):** Standard object with custom `Membership Status` picklist.
2. **Trainers (Custom):** Staff management with `Specialization` tracking.
3. **Fitness Classes (Custom):** Includes `Start/End Date Time` and a **Lookup Relationship** to Trainers.

---

## 📅 Roadmap

### Phase 1: Requirement Analysis & Planning ✅
- [x] Defined Actor-User roles (Member, Trainer, Manager).
- [x] Mapped Business Logic to Salesforce Objects.
- [x] Established Entity-Relationship Diagram (ERD) logic.
- [x] Completed Initial GitHub Repository setup.

### Phase 2: Backend Development & Configuration 🔄
- [x] Custom Object creation (Trainers, Fitness Classes).
- [x] Custom Field implementation (Specializations, Status, Schedules).
- [ ] **NEXT:** Validation Rules (Logic to prevent scheduling errors).
- [ ] **NEXT:** Automation Flows (Membership Expiry Alerts).

### Phase 3: UI/UX Development
- [ ] Customizing Lightning Record Pages.
- [ ] Branding and Navigation menu setup.

### Phase 4: Data Migration, Testing & Security
- [ ] Profile and Permission set configurations.
- [ ] Testing Business Logic with Sample Data.

---

## 👥 The Team
- **Harish M** (Team Lead)
- **Giridharan S** (Member)
- **Lokesh M** (Member)
- **Dinesh Karthick S** (Member)
