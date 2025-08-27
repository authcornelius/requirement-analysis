# Requirement Analysis in Software Development

## Introduction
This repository focuses on **Requirement Analysis** in the software development lifecycle (SDLC).  
The project simulates real-world software development tasks, emphasizing documentation, analysis, and visual representation of requirements for a **Booking Management System**.  

---

## What is Requirement Analysis?
Requirement Analysis is the process of **gathering, analyzing, and defining the requirements of a software system** to ensure that it meets user needs and business objectives.  

It involves:  
- Understanding the needs of stakeholders  
- Translating business goals into functional and non-functional requirements  
- Identifying constraints and acceptance criteria  

**Importance:** It sets the foundation for design, development, and testing, ensuring projects are delivered on time and meet quality standards.  

---

## Why is Requirement Analysis Important?
1. **Clear Project Scope:** Helps define what the system will and won’t do, preventing scope creep.  
2. **Better Planning:** Provides the basis for accurate scheduling, resource allocation, and budgeting.  
3. **Quality Assurance:** Ensures the system meets user expectations for performance, security, and usability.  

---

## Key Activities in Requirement Analysis
- **Requirement Gathering:** Collecting information from stakeholders, users, and business documents.  
- **Requirement Elicitation:** Refining gathered requirements using interviews, surveys, and prototyping.  
- **Requirement Documentation:** Creating detailed specifications, use cases, and diagrams.  
- **Requirement Analysis and Modeling:** Structuring and organizing requirements to identify dependencies and feasibility.  
- **Requirement Validation:** Reviewing requirements with stakeholders to ensure correctness and completeness.  

---

## Types of Requirements

### Functional Requirements
Define what the system **should do**. Examples for the Booking Management System:  
- Users can create, update, or cancel bookings.  
- Admins can manage room availability and pricing.  
- Payment gateway integration for checkout.  

### Non-Functional Requirements
Define **how the system performs** or **constraints**. Examples:  
- **Performance:** System should handle 1000 concurrent bookings.  
- **Security:** User data must be encrypted using SSL/TLS.  
- **Reliability:** System uptime must be ≥ 99.9%.  

---

## Use Case Diagrams
**Use Case Diagrams** visually represent system actors and their interactions with the system. They help stakeholders understand functionalities at a glance.

**Actors:**  
- User  
- Admin  
- Payment System  

**Use Cases:**  
- Create Booking  
- Update Booking  
- Cancel Booking  
- Make Payment  
- Manage Room Availability  
- Set Pricing  
- View Bookings  
- Process Payment  
- Confirm Payment  

**Diagram Example:**  
![Use Case Diagram](alx-booking-uc.png)

---

## Acceptance Criteria
Acceptance criteria define **conditions a feature must meet to be considered complete**.  

**Example – Checkout Feature:**  
- User can select a room and proceed to payment.  
- Payment must be processed successfully, and booking confirmed.  
- Confirmation email sent to the user within 2 minutes.  
- System handles payment failures gracefully with an error message.  

---

## Next Steps
- Commit all files to GitHub: `README.md` and `alx-booking-uc.png`  
- Request **manual QA review** for full assessment  
- Ensure compliance with deadlines
