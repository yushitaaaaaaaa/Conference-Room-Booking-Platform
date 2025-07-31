# Conference Room Booking Platform

A fully developed and production-ready **Conference Room Booking Platform** built from scratch during my internship at **Telecommunications Consultants India Ltd. (TCIL)**. Designed to streamline conference room scheduling, the system provides real-time availability, calendar-based booking, approval workflows, and administrative insights. It supports both user and admin roles, offering a modern, responsive interface with a consistent and professional UI.

This application was successfully deployed for internal use and actively manages daily conference room reservations at TCIL.

*Note: The source code for this project cannot be uploaded to GitHub as it was developed for internal use at TCIL. This repository is intended only to demonstrate the features and UI of the system. All functionalities shown were fully implemented and deployed.*

---

## 🔑 Features

### 👤 User Side

- Login via name, email/phone, and captcha.
- Dashboard showing a **calendar of upcoming bookings**.
- Book a room with:
  - **Time slot selection** (9 AM – 9 PM)
  - **Duration selection** (1 to 3 hours)
  - **isOnline toggle** for virtual conferences
  - **Optional remarks** field
- View, edit, or cancel bookings **before approval**.
- **Calendar view** with modal for days with more than two conferences.
- "Book Now" functionality from **available room cards**.

### 🛂 Admin Side

- Admin **login/register** with captcha protection.
- Dashboard with real-time metrics:
  - Today’s Bookings
  - Total Rooms
  - Total Users
  - Pending Requests
- Admin **calendar** showing all bookings.
- **Assign conference links** or **reject bookings** with reason.
- Full **room management** module:
  - Add, edit, or delete rooms
  - Upload and manage room images
- Analytics section with charts and **date-based filters**.
- Admin can **book on behalf of users**.

---

## ⚙️ Tech Stack

- **Frontend:** HTML, CSS, Bootstrap 5, JavaScript
- **Backend:** PHP (Core), MySQL
- **Libraries & Plugins:**
  - FullCalendar.js – calendar integration
  - Flatpickr – time/date pickers
  - Chart.js – data visualization
  - Font Awesome & Bootstrap Icons – UI icons

---

## 🎨 UI Design

- Polished and consistent **light blue + white theme**.
- Alternating table row colors (white, light blue).
- Unified visual styling for all cards, calendars, and modals.

---
