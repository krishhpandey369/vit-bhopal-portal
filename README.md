# 🎓 VIT Bhopal - Resource Booking & Campus Management System

A comprehensive, role-based web platform designed to digitize and streamline everyday campus operations at VIT Bhopal — from classroom bookings to hostel maintenance, visitor management, and grievance redressal — all in one unified system.

---

## 📖 Overview

Managing a large university campus involves juggling multiple manual processes: booking classrooms for events, reporting hostel maintenance issues, approving visitor entry, and tracking grievances. This project brings all of these workflows into a single, real-time, role-aware web application — eliminating paperwork, reducing delays, and giving every stakeholder (students, faculty, wardens, and administrators) a clear view of what's happening on campus.

The system is built as a single-page application with a live Firebase backend, meaning every booking, issue, or approval updates instantly across all connected users — no page refresh required.

---

## ✨ Key Features

### 🏫 Resource & Classroom Booking
- Browse available classrooms, auditoriums, and labs across Academic Blocks, Architecture Block, and Lab Complex
- Real-time equipment reservation (projectors, mics, etc.)
- Approval workflow for faculty/admin
- Interactive calendar view of all bookings
- Booking cancellation for pending/approved requests

### 🏠 Hostel Issue Management
- Full hostel block directory covering all Boys Blocks (1–8, with wings & extensions), Girls Blocks (1, 2 with wings A–H, 3), Special Block, Amenity Block, and Large Dining Block
- Categorized issue reporting (Electrical, Plumbing, Furniture, Internet/Wi-Fi, Cleaning, or custom "Other")
- Priority tagging (Low / Medium / High)
- Live status tracking with a full complaint timeline
- Warden dashboard to assign staff and update resolution status

### 🚪 Visitor Pass & Gate Security
- Digital visitor pass requests with visit/exit time windows
- Warden approval workflow
- Security gate verification portal with pass-code lookup
- Full visitor log with entry/exit tracking

### 📢 Grievance & Maintenance Redressal
- Campus-wide grievance submission across academic and hostel blocks
- SLA-based resolution tracking with countdown timers
- Department-wise ticket assignment
- Status lifecycle: Pending → In Progress → Resolved

### 👥 Role-Based Access
- **Student** — book resources, raise hostel issues, request visitor passes
- **Faculty** — book resources, view grievances
- **Warden** — manage hostel issues, approve visitor passes
- **Admin** — full oversight of bookings, grievances, and system data

### 🎨 UI/UX
- Clean, responsive design that works across desktop and mobile
- Dark mode support
- Real-time data sync — no manual refresh needed
- Toast/status badges for instant visual feedback

---

## 🛠️ Tech Stack

| Layer          | Technology                              |
|----------------|------------------------------------------|
| Frontend       | HTML5, CSS3, Vanilla JavaScript          |
| Backend/Database | Firebase Firestore (NoSQL, real-time)  |
| Authentication | Firebase Authentication                  |
| Hosting        | GitHub Pages                             |
| Icons/Fonts    | Font Awesome, Google Fonts (Inter)       |

---

## 🚀 Live Demo

🔗 **[View Live Site](https://yourusername.github.io/vit-bhopal-campus-portal/)**

---

## 📸 Modules at a Glance

- Dashboard with role-based quick actions
- Classroom Booking + Calendar
- Hostel Issue Tracker
- Visitor Pass & Gate Logs
- Grievance Redressal System
- Admin Control Panel

---

## ⚙️ How It Works

1. Users select their role and log in via Firebase Authentication.
2. All actions (bookings, issues, grievances, visitor requests) are written to Firestore collections in real time.
3. Firestore's `onSnapshot` listeners keep every connected client synced instantly — if a warden resolves an issue, the student sees the update live.
4. Role-based UI rendering ensures each user only sees actions relevant to their permissions.

---

## 📌 Future Scope

- Push/email notifications for status changes
- Analytics dashboard for admin (booking trends, common complaint categories)
- QR-code based visitor pass verification
- Mobile app version

---

## 👤 Author

Krish Pandey
CSE(AIML) VIT Bhopal University  

---

## 📄 License

This project was developed as part of an academic submission at VIT Bhopal University.
