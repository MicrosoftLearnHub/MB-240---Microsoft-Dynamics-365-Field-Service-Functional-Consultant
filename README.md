# Microsoft Certified: Dynamics 365 Field Service Functional Consultant Associate (MB-240)

[![Microsoft Certification](https://img.shields.io/badge/Microsoft%20Certified-Dynamics%20365%20Field%20Service%20Functional%20Consultant-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Exam Code](https://img.shields.io/badge/Exam%20Code-MB-240-brightgreen?style=for-the-badge&logo=github)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Passing Score](https://img.shields.io/badge/Passing%20Score-700%2F1000-blue?style=for-the-badge)](https://learn.microsoft.com/en-us/credentials/certifications/)
[![Practice Materials](https://img.shields.io/badge/Practice%20Materials-MB-240-orange?style=for-the-badge)](https://www.certsclub.com/microsoft/)

---

## 📖 Table of Contents
1. [Exam Overview](#-exam-overview)
2. [How to Prepare](#-how-to-prepare)
3. [Exam Blueprint & Skills Measured](#-exam-blueprint--skills-measured)
4. [Practice & Preparation Materials](#-practice--preparation-materials)
5. [10 Realistic Demo Practice Questions & Answers](#-10-realistic-demo-practice-questions--answers)
6. [Community Discussion & Study Group](#-community-discussion--study-group)
7. [Detailed Topic Documentation Index](#-detailed-topic-documentation-index)
8. [Official Microsoft Learning Resources](#-official-microsoft-learning-resources)

---

## 🎯 Exam Overview

Exam MB-240 validates functional expertise in configuring and deploying Microsoft Dynamics 365 Field Service, work order lifecycles, Universal Resource Scheduling (URS), inventory, customer assets, connected field service (IoT), and mobile solutions.

### Quick Facts
| Attribute | Specification |
| :--- | :--- |
| **Exam Code** | **MB-240** |
| **Certification Name** | **Microsoft Certified: Dynamics 365 Field Service Functional Consultant Associate (MB-240)** |
| **Passing Score** | 700 / 1000 (Scaled Score) |
| **Official Portal** | [Microsoft Learn Credentials](https://learn.microsoft.com/en-us/credentials/certifications/) |

---

## 🚀 How to Prepare

- 🔗 **Review the Exam MB-240 page for exam registration and other details:**  
  Visit the [Official Microsoft Exam Registration Page](https://learn.microsoft.com/en-us/credentials/certifications/) to review scheduling options via Pearson VUE.
  
- 📚 **Explore the Official Study Guide:**  
  Review the official Microsoft study guide for an itemized breakdown of testable objectives.

- 👥 **Connect with Microsoft Training Services Partners:**  
  Find authorized training partners worldwide at the [Microsoft Training Services Partner Directory](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners).

---

## 📊 Exam Blueprint & Skills Measured

| Domain / Skill Area | Weighting |
| :--- | :---: |
| **Configure Field Service** | **20–25%** |
| **Manage work orders** | **25–30%** |
| **Schedule and dispatch work orders** | **20–25%** |
| **Manage the Field Service mobile app** | **10–15%** |
| **Manage customer assets and inventory** | **10–15%** |
| **Manage Connected Field Service** | **5–10%** |

---

## 💡 Practice & Preparation Materials

For comprehensive practice tests, high-yield scenario questions, and full-length exam simulations, explore the dedicated practice resources for [MB-240](https://www.certsclub.com/microsoft/).

---

## 📝 10 Realistic Demo Practice Questions & Answers

### Question 1 (Domain: Work Order Lifecycle)
**Scenario / Question:** A customer calls requesting emergency repair of an industrial chiller. Which record in Dynamics 365 Field Service acts as the master template that automatically populates the required service tasks, estimated labor duration, replacement parts, and price list onto the newly generated Work Order?
- A) Incident Type
- B) Service Agreement
- C) Opportunity Record
- D) Customer Asset Tag
- **Correct Answer:** **A**
- **Detailed Explanation:** Incident Types act as reusable bundles that automatically populate service tasks, products, services, and skill requirements onto work orders.

---
### Question 2 (Domain: Universal Resource Scheduling (URS))
**Scenario / Question:** A dispatcher needs to find a technician who has 'Master Electrician' certification, speaks German, is located within 25 miles of the customer site, and has available working hours next Tuesday morning. Which tool in Dynamics 365 Field Service performs this multi-factor search?
- A) Schedule Assistant (Find Availability)
- B) Quick Find Search
- C) Outlook Appointment Finder
- D) Excel Filter
- **Correct Answer:** **A**
- **Detailed Explanation:** The Schedule Assistant evaluates resource skills, location/geofencing, working hours, and capacity to filter and rank the best-matched bookable resources.

---
### Question 3 (Domain: Agreements & Maintenance)
**Scenario / Question:** You need to automatically generate preventive maintenance work orders on the 1st of every month for 100 HVAC units installed across corporate campuses. Which Field Service feature automates this recurring process?
- A) Field Service Agreements (Booking Setup with Recurrence Schedule)
- B) Manual Work Order cloning
- C) Power Automate button click
- D) Outlook Calendar recurring series
- **Correct Answer:** **A**
- **Detailed Explanation:** Field Service Agreements define recurring service terms, automatically generating work orders and invoices based on defined recurrence schedules.

---
### Question 4 (Domain: Inventory Management)
**Scenario / Question:** A technician needs to take 5 circuit breakers from the main central warehouse and load them into their service truck inventory. Which record must be created to track the movement of parts between inventory locations?
- A) Inventory Transfer
- B) Purchase Order
- C) Return Merchandise Authorization (RMA)
- D) Sales Invoice
- **Correct Answer:** **A**
- **Detailed Explanation:** An Inventory Transfer records the physical reallocation and ledger tracking of items moving from one warehouse/truck to another.

---
### Question 5 (Domain: Connected Field Service (IoT))
**Scenario / Question:** An IoT temperature sensor on an industrial freezer exceeds 4°C. The Azure IoT Hub detects the threshold anomaly. How does Connected Field Service automatically react to resolve the issue proactively?
- A) Ingests the telemetry as an IoT Alert, attempts an automated remote reset command, and creates an urgent Work Order if the anomaly persists
- B) Shuts down the entire factory network
- C) Deletes the asset record
- D) Reboots the Dynamics 365 tenant
- **Correct Answer:** **A**
- **Detailed Explanation:** Connected Field Service ingests IoT alerts, triggers automated diagnostic commands, and escalates to work orders dispatched to technicians before equipment fails.

---
### Question 6 (Domain: Mobile Offline Capabilities)
**Scenario / Question:** Technicians frequently work in underground basements without cellular connectivity. What must you configure in Dynamics 365 Field Service to ensure technicians can view customer assets, update work tasks, and capture digital signatures without internet?
- A) Mobile Offline Profiles with targeted entity sync filters
- B) Require technicians to print paper copies
- C) Increase 5G antenna strength
- D) Use Remote Desktop Protocol
- **Correct Answer:** **A**
- **Detailed Explanation:** Mobile Offline Profiles define the exact data tables, sync filters, and relationships downloaded locally to mobile devices for seamless offline operation.

---
### Question 7 (Domain: Resource Scheduling Optimization (RSO))
**Scenario / Question:** An enterprise wants to automatically reschedule 500 daily service bookings overnight to minimize travel time across the city while prioritizing high-priority emergency work orders. What should you deploy?
- A) Resource Scheduling Optimization (RSO)
- B) Schedule Board manual drag
- C) Power BI historical report
- D) Windows Task Scheduler
- **Correct Answer:** **A**
- **Detailed Explanation:** Resource Scheduling Optimization (RSO) is an automated add-in that optimizes routes, minimizes travel distances, and reallocates bookings based on business objectives.

---
### Question 8 (Domain: Field Service Inspections)
**Scenario / Question:** You need technicians to complete a standardized 20-question safety checklist with photo attachments and pass/fail validations directly inside the Field Service Mobile app while servicing equipment. Which feature should you configure?
- A) Field Service Inspections
- B) PDF form emailed to the tech
- C) Word Document template
- D) Text file on OneDrive
- **Correct Answer:** **A**
- **Detailed Explanation:** Field Service Inspections are digital forms linked to service tasks that guide technicians through structured checklists and validation steps.

---
### Question 9 (Domain: Mixed Reality)
**Scenario / Question:** A junior field technician on-site encounters an unfamiliar complex medical machine and needs real-time heads-up video guidance and 3D spatial annotations from a remote senior specialist. Which application integrates natively with Field Service Mobile?
- A) Microsoft Dynamics 365 Remote Assist
- B) Skype Consumer
- C) Windows Paint
- D) Microsoft PowerPoint
- **Correct Answer:** **A**
- **Detailed Explanation:** Dynamics 365 Remote Assist enables one-click video calls with mixed reality 3D annotations directly from the Field Service mobile app to remote experts.

---
### Question 10 (Domain: Not-to-Exceed (NTE))
**Scenario / Question:** A customer specifies that emergency service repairs must not exceed $1,500 without prior written approval. How does Dynamics 365 Field Service enforce this spending limit on work orders?
- A) Not-to-Exceed (NTE) rules configured on the Account or Work Order
- B) Disabling technician mobile access
- C) Blocking credit cards
- D) Manually deleting invoice rows
- **Correct Answer:** **A**
- **Detailed Explanation:** Not-to-Exceed (NTE) capabilities set financial caps on work orders, warning or blocking technicians and dispatchers when costs or prices exceed approved limits.

---

## 💬 Community Discussion & Study Group

Have questions regarding MB-240 concepts, study plans, or exam strategies?
- 💬 **Ask a question or start a topic:** [GitHub Discussions](https://github.com/MicrosoftLearnHub/MB-240---Microsoft-Dynamics-365-Field-Service-Functional-Consultant/discussions)
- 🐛 **Report corrections or suggest updates:** [GitHub Issues](https://github.com/MicrosoftLearnHub/MB-240---Microsoft-Dynamics-365-Field-Service-Functional-Consultant/issues)
- 🤝 **Contribute:** Open a Pull Request to share study notes, architecture diagrams, and review materials.

---

## 📂 Detailed Topic Documentation Index

- 📘 [01-configure-field-service.md](./docs/01-configure-field-service.md)
- 📘 [02-manage-work-orders.md](./docs/02-manage-work-orders.md)
- 📘 [03-schedule-and-dispatch.md](./docs/03-schedule-and-dispatch.md)
- 📘 [04-field-service-mobile-app.md](./docs/04-field-service-mobile-app.md)
- 📘 [05-customer-assets-and-inventory.md](./docs/05-customer-assets-and-inventory.md)
- 📘 [06-connected-field-service-iot.md](./docs/06-connected-field-service-iot.md)
- 📘 [07-official-resources-and-links.md](./docs/07-official-resources-and-links.md)

---

## 🌐 Official Microsoft Learning Resources

- 🌐 [Microsoft Learn Certification Directory](https://learn.microsoft.com/en-us/credentials/certifications/)
- 🌐 [Microsoft Learn Free Interactive Modules](https://learn.microsoft.com/en-us/training/)
- 🌐 [Find a Microsoft Training Services Partner](https://learn.microsoft.com/en-us/credentials/support/help#training-services-partners)

---

### 🛡️ Disclaimer
*This repository contains educational study notes, architecture summaries, and reference documentation compiled from publicly available official Microsoft Learn documentation. Microsoft, Azure, and Microsoft Entra are trademarks of the Microsoft group of companies.*
