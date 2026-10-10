 🏥 Diagnostic Test Center Portal using ServiceNow

A centralized medical diagnosis solution built on the ServiceNow platform using Service Portal that enables fast, accurate, and automated booking of diagnostic tests and delivery of medical reports, replacing queues, phone calls, and paper reports with a seamless online experience.

📌 Overview

Traditional diagnostic center booking involves long queues, manual record keeping, overbooked slots, and paper reports that are easy to lose. This project digitizes the entire journey, from browsing tests and selecting a slot to paying, tracking the sample, and receiving the report, while giving lab technicians and administrators automated workflows and secure, role-based control.

 🎯 Objectives

1. Enhance Patient Convenience
   Provide a guided, user-friendly Service Portal where patients can browse tests and packages, choose date and time slots, and request lab visits or home sample collection.

2. Increase Operational Efficiency
   Automate booking, approvals, status updates, and reminders using Flow Designer and scheduled jobs to reduce manual work and errors.

3. Ensure Accurate Scheduling
   Use real-time slot availability validation to prevent overbooking and overlapping appointments.

4. Improve Billing Transparency
   Apply dynamic pricing based on selected tests, packages, home collection, and discount rules, with payment confirmation built into the workflow.

5. Protect Patient Data
   Use role-based ACLs and patient-level data filtering so that only authorized users can view, update, or manage appointments and reports.

✨ Key Features

🧪 Test & Package Catalog: browse available diagnostic tests and packages with prices

📅 Guided Slot Booking: select preferred date and time slot through Service Portal

🏠 Home Sample Collection: optional home collection with conditional form fields

⏱️ Real-Time Slot Validation:prevents overbooking and overlapping appointments

💰 Dynamic Pricing: automatic cost calculation with tests, packages, home collection, and discounts

🤖 Automated Workflows: validation, payment confirmation, and optional approvals handled by ServiceNow Flow Designer

🔁 Cancellation & Rescheduling: appointment records updated with cancellation rules applied

🔔 Email Notifications: booking, payment receipt, reminders, sample collection updates, report availability, and cancellation alerts

🗓️ Scheduled Jobs: automatic status updates (Scheduled, Sample Collected, Processing, Report Ready, Completed) and missed appointment marking

📄 Report Management: lab technicians upload reports and patients view or download them

🛠️ Admin Control: manage the test catalog, pricing, slots, technician assignments, and workflow settings through custom tables and forms

🔐 Role-Based Security: ACLs for Patients, Lab Technicians, and Admins

 👥 User Roles

| Role | What they do |
|---|---|
| Patient | Browse tests, book appointments, pay, track status, cancel or reschedule, view reports |
| Lab Technician | View assigned appointments, update sample status, upload reports |
| Admin | Manage catalog, pricing, slots, technicians, workflows, and approvals |

 🛠️ Tech Stack

ServiceNow, Service Portal, HTML, CSS, AngularJS, Client & Server Scripts, UI Policies, Script Includes, GlideRecord, Flow Designer, Scheduled Jobs, ACLs, Event-driven Email Notifications

 🚀 Future Enhancements

💳 External payment gateway integration
📱 SMS notifications
👨‍⚕️ Doctor portal integration
📊 Analytics expansion

 👤 Author

Srini R

