# Hotel_Reservation_CRM_Project_salesforce1
*Hotel CRM System
Problem Statement

Managing a hotel involves multiple operations such as booking reservations, managing guest information, assigning rooms, processing payments, and handling feedback. Manual processes or disconnected systems lead to errors, inefficiencies, and poor customer experience. Hotels often struggle with:

Double-bookings or incorrect reservations.

Lack of visibility into room availability and occupancy.

Difficulty tracking guest preferences and feedback.

Manual calculation and tracking of payments.

Security and access control for sensitive guest data.

Goal:
Build a centralized CRM system for hotels to manage guests, reservations, rooms, payments, and feedback efficiently, while automating repetitive tasks and ensuring secure data handling.

Solution Overview

The Hotel CRM System is built on Salesforce and includes:

Guest Management: Maintain guest contact information, booking history, and preferences.

Room & Reservation Management: Track room availability, assign rooms, and manage check-in/check-out processes.

Payment Tracking: Record payment methods, status, and generate invoices.

Feedback Collection: Collect and manage guest feedback for service improvement.

Automation: Use Salesforce Flows and Validation Rules to prevent errors and automate processes like room status updates and notifications.

Security Measures: Field-Level Security (FLS), Login Hours, and IP restrictions to protect sensitive data.

Features

Custom Objects: Room, Reservation, Payment, Feedback.

Validation Rules: Ensure correct check-in/check-out dates.

Approval Processes: For VIP or group bookings.

Record-Triggered Flows: Update room status automatically.

Screen Flows: Easy booking interface for receptionists.

Email Alerts & Notifications: Automated confirmations, reminders, and housekeeping alerts.

Reports & Dashboards: Insights into reservations, occupancy, and payments.

Integration: Payment gateways, SMS reminders, Google Maps API, and Experience Cloud portal.

Technologies Used

Salesforce (Lightning Experience)

Salesforce Flow & Automation

Apex (if required for custom logic)

Data Import Wizard & Data Loader

External APIs (Payment Gateway, SMS, Maps)**
