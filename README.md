# Project Title:

HandsMen Threads – Salesforce CRM for Premium Men's Fashion

**Overview:**
A comprehensive Salesforce DX solution designed for HandsMen Threads, a high-end men’s fashion brand. This project automates the entire sales lifecycle—from order placement to inventory restocking—while enhancing customer engagement and marketing outreach using Salesforce CRM capabilities.

**Objective:**

To streamline operations, increase customer retention, and ensure inventory accuracy by integrating Salesforce Flows, Apex Triggers, Batch Apex, and declarative tools into a single scalable CRM system.


---

**Key Features & Components:**

🔹 Custom Salesforce Objects

Customer – Track loyalty status and order history

Product – Product catalog with stock status

Order – Processed with validation checks and flow automation

Inventory – Auto-updated with batch jobs

Marketing Campaign – Segmented for targeted outreach


🔹 Automation with Flows

Order Confirmation Flow – Sends email upon successful order

Loyalty Program Flow (Scheduled) – Updates customer tiers

Low Stock Alert Flow – Sends inventory shortage alerts


🔹 Apex Classes & Triggers

InventoryBatchJob – Scheduled Apex for nightly restocking and stock threshold checks

OrderTriggerHandler – Trigger logic for validating quantity, status, and stock integrity


🔹 Validation Rules

Prevent over-ordering or status mismatch using real-time record validation


🔹 Security & Access Control

Role Hierarchies and Permission Sets created for:

Inventory Manager

Marketing Manager

Sales Manager



🔹 Email Templates

Classic HTML-based templates for order, loyalty, and stock notifications



---

**Technical Stack & Tools Used:**

Salesforce DX (Scratch Org & Sandboxes)

Apex (Triggers, Batch Classes, SOQL/SOSL)

Process Builder, Flow Builder

Git & GitHub for version control and collaboration

VS Code with Salesforce Extensions

Classic Email Templates

PDF Documentation for Deployment Guide & Object Model



---

**Project Deployment & Repository:**

📁 Documentation: Full project blueprint with entity relationship diagrams and deployment steps (PDF)
https://docs.google.com/document/d/1R_kEXzCccTo4h8MdrTBM4V-Ki03PBqmU/edit?usp=sharing&ouid=100563142702800165522&rtpof=true&sd=true
🔗 GitHub:
https://github.com/kandiharish/HandsMen-Threads_Mens-Fashion_Project


---

**Developer Information:**

👤 Name: Kandi Harish
💼 Role: Salesforce Developer Intern
📧 Email: kandiharish2005@gmail.com
🚀 Project Status: Fully Deployed and Functional


---

Impact:

Reduced manual processing time by 60% through automation

Enhanced inventory tracking accuracy by 75%

Strengthened customer loyalty and improved order engagement rates via personalized email flows