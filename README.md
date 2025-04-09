# 🎓 Attendance Management Portal

The Attendance Management Portal is a role-based web application built using ASP.NET (C#) and SQL Server. It is designed to streamline and digitize the process of managing attendance in educational institutions. The system supports three types of users: Admin, Staff, and Students, with specific features and permissions for each.

## 📌 Project Overview
A web-based portal developed as part of a Final Year College Project.

Focuses on digital attendance tracking, centralized records, and role-based access.

Designed to enhance efficiency, reduce paperwork, and improve communication between administration, staff, and students.

## 👥 User Roles & Features
**🔐 Admin (Principal/Institution Head):-**

-Login access to manage the entire system.

-Add and manage:- Staff members , Divisions/Classes , System settings

-View complete attendance reports across the institution.

**👨‍🏫 Staff:-**

- Add and manage student details.

-Mark attendance as Present/Absent.

-View and edit student attendance records.

-Generate subject-wise or student-wise reports.

**👨‍🎓 Student**

-Login to personal dashboard.

-View individual attendance records.

-Submit Leave Requests online.

-File Complaints directly through the portal.

## 🛠️ Tech Stack

-Frontend: ASP.NET Web Forms / Razor Pages

-Backend: C# (.NET Framework)

-Database: Microsoft SQL Server

-Tools/IDE: Visual Studio, SSMS

-Authentication: Session-based login with role identification

## 🗂️ Project Structure

graphql
Copy
Edit
/AttendanceManagementPortal
│
├── /App_Code           # Business logic (C# classes)
├── /App_Data           # SQL Database (.mdf file)
├── /Pages              # ASPX Web Forms / Razor Pages
├── /Assets             # CSS, JS, images
├── /Admin              # Admin dashboard pages
├── /Staff              # Staff module pages
├── /Student            # Student module pages
└── Web.config          # Configuration settings
📋 Key Functionalities
📚 Role-based Login System (Admin, Staff, Student)

✅ Daily Attendance Marking (by Subject or Division)

📈 Attendance Reports with Filters

📄 Leave Request Submission (by students)

📬 Complaint Management (Student to Admin/Staff)

🔐 Secure Authentication & Session Management

📊 Attendance Statistics Overview (for Admin)

## 💻 Setup Instructions
Clone or Download the Repository

bash
Copy
Edit
git clone https://github.com/vikasbhosale-45/Attendance-management-portal.git
Open in Visual Studio

Open the .sln file in Visual Studio.

Set Up the Database

Attach the SQL database file from App_Data OR

Run the provided .sql script in SQL Server Management Studio (SSMS).

Configure the Connection String

Update the Web.config file with your SQL Server details.

Run the Project

Press F5 in Visual Studio or use IIS Express to launch.

## 🧪 Sample Test Logins
(Username / Password)

Admin: admin / 123

Staff: staff / 1122

Student: student / 2211

## 📸 Screenshots
(Add UI screenshots of each user role dashboard, attendance pages, reports, etc.)

📄 Project Documentation
Included in the /Docs folder:

ER Diagram

Use-Case Diagram

Flowchart

System Architecture

Project Report (PDF/Word)

📌 Future Enhancements
📱 Responsive mobile version using ASP.NET Core + Blazor or Angular.

🔔 Email or SMS notifications for attendance alerts.

🧠 Integration with biometric/RFID devices.

📲 Android/iOS App using Xamarin or MAUI.

🙋‍♂️ Developed By
Your Name

Final Year B.E./B.Tech Student, [Your College Name]

[your.email@example.com]

📃 License
This project is open for academic reference and learning purposes.
