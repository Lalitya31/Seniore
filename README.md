# Seniore
Seniore is a web-based platform that connects junior university students with seniors for structured mentorship, academic guidance, and peer support. The system is designed to reduce onboarding friction for juniors while enabling seniors to share experience in a controlled, time-bound, and accountable manner.

# Problem Statement
Junior students often struggle with academic navigation, course selection, internships, and campus life due to lack of accessible peer guidance. At the same time, senior students possess valuable institutional knowledge but lack a structured way to mentor juniors beyond informal chats and scattered groups.
Existing solutions (WhatsApp groups, Discord servers, spreadsheets) are unstructured, noisy, and difficult to moderate. Seniore provides a clear, role-based system to enable meaningful junior–senior interactions within a university ecosystem.
______________________________________________________________________________________________________________________________________________________________________________________________________
## **Tech Stack**
**Frontend**
- React
-HTML / CSS
-Accessibility-focused UI components

**Backend**
-Python (Flask)
-RESTful APIs
-Database
-Relational database (users, profiles, sessions, feedback)

**Version Control**
-Git, GitHub

## **Core Functionality**

- Role-based onboarding (Junior / Senior)
- Profile creation with department, year, interests
-  Availability-based matching
- Scheduled 1:1 or small-group sessions
- Session feedback and reporting
- Moderation and blocking mechanisms
- Clear interaction boundaries (no open-ended DMs)

## **System Overview**
Client (Web UI)
   ↓
API Layer (Flask)
   ↓
Matching & Session Logic
   ↓
Database (Users, Sessions, Feedback)

## **Key Design Considerations**

1. Clarity: explicit roles, visible session states, predictable flows
2. Scalability: supports growth across departments and batches
3. Safety: reporting, moderation, limited interaction scope
4. Usability: simple navigation, minimal cognitive load

## **Project Status**
🚧 Early-stage development / MVP in progress
Core flows and system design are being implemented incrementally.
