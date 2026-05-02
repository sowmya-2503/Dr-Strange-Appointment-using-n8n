# Dr-Strange-Appointment-using-n8n
# AI-Powered Patient Appointment Booking System Using n8n

## Project Overview

This project is an AI-powered patient appointment booking system built using n8n. It helps clinics and hospitals automate the appointment booking process using AI.

Patients can send messages through WhatsApp or chat, and the AI Agent automatically understands the request, checks doctor availability, creates appointments, stores patient details, and sends confirmation messages.

This reduces manual work, saves time, and improves patient service.

---

## Problem Statement

Many clinics and hospitals still manage appointments manually.

This creates problems such as:

- Time-consuming appointment booking
- Manual checking of doctor availability
- Errors in patient data entry
- Delays in sending confirmation messages
- Increased workload for hospital staff

This project solves these problems using workflow automation.

---

## Tools Used

- n8n
- OpenAI Chat Model
- Google Sheets
- Google Calendar
- Gmail
- WhatsApp Chat Interface

---

## Workflow

### Step-by-Step Process

Step 1 → Patient sends a message through WhatsApp or chat

Step 2 → “When chat message received” trigger starts the workflow

Step 3 → AI Agent reads and understands the request

Step 4 → OpenAI Chat Model processes the appointment details

Step 5 → Google Calendar checks available appointment slots

Step 6 → If available, a new appointment event is created

Step 7 → Patient details are stored in Google Sheets

Step 8 → Confirmation message is sent using Gmail

Step 9 → Appointment is successfully booked

---

## Prompt Used

Create an AI-powered appointment booking workflow using n8n where patients can send messages through WhatsApp or chat. The AI Agent should understand the request, check available slots in Google Calendar, create an appointment event, store patient details in Google Sheets, and send a confirmation message using Gmail.

---

## Final Output

The final system includes:

- Automatic patient appointment booking
- AI-based request understanding
- Calendar availability checking
- Event creation in Google Calendar
- Patient record storage in Google Sheets
- Automated confirmation email/message sending

This creates a smart and efficient hospital appointment management system.

---

## Challenges Faced

- Connecting multiple services in n8n
- Setting up Google Calendar integration
- Managing workflow logic correctly
- Understanding AI Agent memory and tools
- Handling appointment availability checking

---

## Learning Outcomes

From this project, I learned:

- Workflow automation using n8n
- AI Agent integration in real-world systems
- API connections with Google services
- Prompt engineering basics
- Practical automation for hospitals and clinics

This project helped me understand how AI can solve real-world business problems efficiently.

---

## Conclusion

The AI-Powered Patient Appointment Booking System improves hospital efficiency by reducing manual work and automating appointment handling.

It provides faster service, better patient management, and smarter workflow automation using AI and n8n.
<img width="1907" height="1011" alt="Screenshot 2026-04-20 200725" src="https://github.com/user-attachments/assets/f48a0887-9589-4593-8903-252250e554b1" />


Demo link
https://ssssowmyaaaa.app.n8n.cloud/webhook/56ec5abe-8f8d-45de-ada5-71569c0c1d49/chat
