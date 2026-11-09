# Nexus Cowork - Centralized Coworking Space Management System
**Course:** CSC 326: Web Development (HTML, CSS, JavaScript)  
**Student Name:** Piyush Kumar ,sana seemab ,aditya kumar  
**Registration Number:** 12611741 ,12611225 ,12612358  
**Section:** K4P26WR  
**Domain / Track:** Tech Venture  
**University:** Lovely Professional University (LPU), Phagwara, Punjab  

---

## 📌 Problem Statement
The organization needs a centralized application for coworking space management, because spreadsheets, paper records, or disconnected communication can lead to duplicate data, missed updates, and inefficient operations.

## 🎯 Project Objective
Develop a role-based coworking space management system that centralizes core records, user interactions, workflows, and status reporting around Lovely Professional University (LPU) campus and neighboring hubs.

---

## 🚀 Key Features Implemented

1. **Centralized Core Records**:
   - Cabins, dedicated desks, meeting rooms, hot desks, and podcast media studios located across authentic LPU vicinities:
     * *Uni-Mall Innovation Loft* (Gate 1, LPU Campus)
     * *Law Gate Tech Haven* (Law Gate Commercial Strip)
     * *Maheru Startup Pod* (Maheru Road / North Gate)
     * *GT Road Executive Boardroom* (Chaheru Highway)
     * *Block 34 Media & Podcast Bay* (LPU Central Campus)
     * *Urban Estate Creative Suite* (Urban Estate Phase 2)
   - Real-time status flags: `Available` (Green), `Occupied` (Amber), and `Maintenance` (Red).

2. **Role-Based Access Control**:
   - **Member / Student View**: Browse spaces, search by keyword/amenity, filter by category/location, book a space, track reservations, and view digital receipts.
   - **Admin / Facility Manager View**: Add new coworking spaces to the central inventory, toggle maintenance status, delete spaces, and audit all student reservations.

3. **Complete User Interactions & Workflows**:
   - End-to-end interactive booking modal with live duration stepper and price calculation (`₹/hr * Duration`).
   - Generates digital invoices with instant confirmation and print capability.
   - User interaction workflow: Check-in, Check-out (which auto-frees the space back to Available), and Cancel reservation.

4. **Live Status Reporting & Analytics**:
   - Real-time KPI summary cards: Total Spaces, Available Spaces, Active Bookings, and Occupancy Rate (%).
   - Interactive visual charts using Chart.js:
     * **Donut Chart**: Space Status Distribution (Available vs. Occupied vs. Maintenance).
     * **Bar Chart**: Revenue by Space Category (Cabins vs. Desks vs. Studios).

5. **Data Persistence**:
   - Built-in `localStorage` synchronization keeps all bookings, status toggles, and newly created spaces preserved across page refreshes.
   - "Reset Demo Data" button to restore initial clean state at any time.

---

## 💻 Tech Stack
- **HTML5:** Semantic Elements (`<header>`, `<main>`, `<section>`, `<nav>`, `<table>`, `<dialog>`)
- **CSS3:** Tailwind CSS + Custom CSS (`style.css`)
- **JavaScript:** ES6+ Vanilla JavaScript (DOM Manipulation, Event Listeners, State Management)
- **Visual Analytics:** Chart.js 4.4.1
# centralized-coworking-system
