# 📘 Konoz | Student Attendance and Management System

<img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/c00dcbdf448ce3100b94a325c9591c476873bfd7/Cover-01.png" alt="Konoz"/>

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
## 🔥 Screenshots
<table align="center">
  <tr>
    <td align="center">
      <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/4d6427ec1a355296c081237b7706f9636528c640/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-28%20235229.png" alt="Project 1" width="300px"/>
      <br/>
      <b>Screen 1</b>
    </td>
    <td align="center">
      <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/4d6427ec1a355296c081237b7706f9636528c640/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-28%20235308.png" alt="Project 2" width="300px"/>
      <br/>
      <b>Screen 2</b>
    </td>
    <td align="center">
    <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/3961ae84c5997b83401f34ca941ee0367631d3d3/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-29%20005032.png" alt="Project 2" width="300px"/>
      <br/>
      <b>Screen 3</b>
    </td>
    
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/4d6427ec1a355296c081237b7706f9636528c640/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-28%20235408.png" alt="Project 3" width="300px"/>
      <br/>
      <b>Screen 4</b>
    </td>
    <td align="center">
      <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/4d6427ec1a355296c081237b7706f9636528c640/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-28%20235431.png" alt="Project 3" width="300px"/>
      <br/>
      <b>Screen 5</b>
    </td>
    <td align="center">
      <img src="https://github.com/Abdelrhman-Ahmed1/Konoz-Student-Management-Application/blob/4d6427ec1a355296c081237b7706f9636528c640/%D9%84%D9%82%D8%B7%D8%A9%20%D8%B4%D8%A7%D8%B4%D8%A9%202025-04-28%20235523.png" alt="Project 3" width="300px"/>
      <br/>
      <b>Screen 6</b>
    </td>
  </tr>
</table>


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
## License
This project is licensed under the MIT License.

## Author
- **Name:** Abdelrhman Ahmed
- **Department:** Software Engineer
- **Date of Publish:** 27/8/2024
- **LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/%D9%90abdelrhman-ahmed-82609b296/)

