# Conference Room Booking Platform

A fully developed and production-ready **Conference Room Booking Platform** built from scratch during my internship at **Telecommunications Consultants India Ltd. (TCIL)**. Designed to streamline conference room scheduling, the system provides real-time availability, calendar-based booking, approval workflows, and administrative insights. It supports both user and admin roles, offering a modern, responsive interface with a consistent and professional UI.

This application was successfully deployed for internal use and actively manages daily conference room reservations at TCIL.

*Note: The source code for this project cannot be uploaded to GitHub as it was developed for internal use at TCIL. This repository is intended only to demonstrate the features and UI of the system. All functionalities shown were fully implemented and deployed.*

---

## 🔑 Features

### 👤 [User Side](#-user-screens)

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

### 🛂 [Admin Side](#-admin-screens)

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

## 📸 Screenshots

### 👤 User Screens

<table align="center">
  <tr>
    <td align="center">
      <b>Home</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/352880a0-cedf-4eac-a9eb-d2b034133237" />
    </td>
    <td align="center">
      <b>Profile</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/a8c82b66-4a08-4a6e-a074-9243dde8a733" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Dashboard</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/3bd6e968-1d1c-4eba-85f2-6db84a2d5682" />
    </td>
    <td align="center">
      <b>Rooms Modal</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/ac3b2825-499e-43e2-9cf2-e51180b9a6a8" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Time Slots</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/03095a54-2288-448d-8855-4a7037d3433e" />
    </td>
    <td align="center">
      <b>Available Rooms</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/48529b36-58c9-4d54-ba77-a231a7d3835a" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Update Profile</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/c2d2299a-a10f-4b17-99f0-1baf69f4753c" />
    </td>
    <td align="center">
      <b>Book Room Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/ecdd6f4d-9c20-41c9-bffe-0302c3250818" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Edit Booking Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/025b5de8-7361-45c8-93a1-c25e695c4c23" />
    </td>
    <td align="center">
      <b>Cancel Booking Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/c98e0684-89f7-4e72-91a4-a8d85d3f2bdb" />
    </td>
  </tr>
</table>

---

### 🛠️ Admin Screens

<table align="center">
  <tr>
    <td align="center">
      <b>Login</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/9f8ba346-63a8-4680-b960-702f99ada6e6" />
    </td>
    <td align="center">
      <b>Register</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/e2122ec1-00e2-48ce-ac00-824783bbf6c6" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Dashboard</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/67d0a567-76ba-4634-8d55-99364593cdaa" />
    </td>
    <td align="center">
      <b>Booking Requests</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/6c8d3f97-794b-4156-9267-322efd6bc3c4" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Approve Booking Modal</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/6c52a92e-e44c-4f0e-a362-e12a23d92151" />
    </td>
    <td align="center">
      <b>Reject Booking</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/0494e153-ca6a-4832-9ecc-0062b43cbe21" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Manage Rooms</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/c7a469d4-67e5-4d6a-ad83-db9603bbfb7f" />
    </td>
    <td align="center">
      <b>Add Room Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/caabe2fe-77e4-4617-aa71-900358c491f3" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Edit Room Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/3556fad5-f73a-4704-812d-e89c2fcfff37" />
    </td>
    <td align="center">
      <b>Delete Room Form</b><br>
      <img width="400" src="https://github.com/user-attachments/assets/e84ff3f9-2ec9-435f-87e3-ac8425c50d46" />
    </td>
  </tr>
</table>

---

### ✉️ Email Notifications

<table align="center">
  <tr>    
    <td align="center">
      <b>Booking Approved</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/473a2a9e-876c-4c9c-a469-9328a94a9075" />
    </td>
    <td align="center">
      <b>Booking Rejected</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/8bbcdae2-fd35-4205-932d-e628a40dc47b" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <b>Booking Submitted</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/159f3594-17f6-40a7-ab33-7e5721bd18ec" />
    </td>
    <td align="center">
      <b>Booking Updated</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/b840a2c5-e6fc-438b-a4b4-76092d1c447a" />
    </td>
  </tr> 
  <tr>    
    <td align="center">
      <b>Booking Cancelled</b><br>
      <img height="200" src="https://github.com/user-attachments/assets/46c028dc-33c9-43f8-badd-59ea0c791c94" />
    </td>
    <td></td>
  </tr>
</table>

---

## 📄 License

This project was developed as part of an internship at **Telecommunications Consultants India Ltd. (TCIL)**.

© 2025 TCIL. This software is intended for internal demonstration and operational use only.

Developed by **[Yushita Kalra]** as an intern.

---
