# 📘 Student Attendance and Management System

## 🔢 Description
This project is a **student management system** built with **Flet** (Python GUI framework) and **SQLite** (local database). It manages **student attendance**, **student information**, and allows **synchronization with a server** for backup or collaboration.

The system offers:
- 👨‍🎓 **Add new students** to different sections (First, Second, Third secondary grades).
- 🗓️ **Track attendance and absences** for each student.
- 💻 **Synchronize** local data with a remote **Flask server** over HTTP and WebSocket.
- 📦 **Upload and download** student databases (`data.db`, `DONT OPEN.db`) to/from the server.
- 📊 **Export data** to **Excel files** (.xlsx) for reporting.
- 🔐 **User authentication** (login/logout system) to protect administrative actions.
- 🎨 **Modern UI** using Flet with **dark/light theme switcher**.
- 🏷️ **Automatic day detection** (e.g., Friday = "Holiday", Saturday = "Alpha Center", etc.).
- 📸 **Student photo management**, with image uploads and display inside dialogs.
- 🛠️ **Edit and update** student records inside the database.
- 📨 **Send files and attendance lists** to the server.
- 🛡️ **Server availability detection** (e.g., server online/offline status).
- 📋 **Local client storage** (save attendance temporarily using Flet's `client_storage`).

---

## ⚙️ Technologies Used
- **Python 3**
- **Flet** (for cross-platform GUI)
- **SQLite** (local database)
- **HTTPX** and **Requests** (for server communication)
- **Pandas** (for exporting to Excel)
- **Flask server** (for backend communication, not included but implied)

---

## 🚀 Major Features
| Feature                  | Description |
|:-------------------------|:------------|
| Attendance Management    | Take, track, and save attendance locally or to a server. |
| Student Registration     | Add new students into different grades with full details (name, address, phone, school, etc.). |
| Image Handling           | Students can have associated images (optional) fetched from GitHub links or local server. |
| Backup & Restore         | Sync your local database with a Flask server easily (upload/download buttons). |
| Authentication           | Admin login system to restrict sensitive actions (adding/editing students, exporting data). |
| Excel Export             | Save student data into `.xlsx` format per section easily. |
| Dynamic UI               | Arabic language support, day-based center assignment, theme switch (Dark/Light). |

---

## 🔥 Overall
✅ This program is a **full student attendance and management solution** — modern, fast, supports remote syncing, and very customizable.
✅ It can be easily expanded with more features like notifications, automated reports, etc.

---

> Developed with ❤️ by Abdelrhman Ahmed

