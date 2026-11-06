# SMS - School Management System

A modern, secure, and responsive School Management System for **Grades 9–12**, built with PHP 8+, MySQL, PDO, JavaScript, and Bootstrap 5. The system supports academic administration, student and teacher management, attendance tracking, examinations, grading, report cards, announcements, and academic reporting.

![Status](https://img.shields.io/badge/status-active-success)
![PHP](https://img.shields.io/badge/PHP-8%2B-blue)
![MySQL](https://img.shields.io/badge/MySQL-8%2B-blue)
![License](https://img.shields.io/badge/license-Proprietary-lightgrey)

---

## Features

### Core Modules

- **Authentication:** Login, logout, password changes, password reset, and brute-force throttling.
- **Role-Based Access Control:** Admin, teacher, student, and parent roles with permissions.
- **Admin Dashboard:** Statistics, charts, recent activity, and quick actions.
- **Academic Management:** Academic years, terms, grades 9–12, sections, and subjects.
- **Student Management:** Student records, enrollment, photo uploads, guardian management, and profiles.
- **Teacher Management:** Teacher records, assignments, and class teacher designation.
- **Attendance:** Attendance entry, history, reports, and printable sheets.
- **Examinations:** Quizzes, assignments, midterm and final examinations, with status workflows.
- **Marks Entry:** Marks entry with percentage calculations and grade previews.
- **Grading Rules:** Configurable grade boundaries, points, letters, and remarks.
- **Results:** Student examination results.
- **Report Cards:** Printable school-branded report cards.
- **Announcements:** Targeted announcements for school communities, grades, and sections.
- **Reports:** Academic performance, attendance analytics, student directories, and class summaries.
- **Role Dashboards:** Personalized dashboards for students, teachers, and parents.
- **Administration:** School settings, user management, permissions, and audit logs.
- **Security:** CSRF protection, session fingerprinting, rate limiting, security headers, and `.htaccess` hardening.

### User Interface

- Responsive desktop, tablet, and mobile layouts.
- Dark mode support.
- Collapsible sidebar and mobile navigation.
- Breadcrumbs, notifications, and profile menus.
- Toast notifications, empty states, and loading states.
- Accessible and semantic HTML.

---

## Technology Stack

| Layer | Technology |
|---|---|
| Backend | PHP 8+, PDO |
| Database | MySQL 8+ / MariaDB 10.4+ |
| Frontend | HTML5, CSS3, JavaScript |
| UI Framework | Bootstrap 5 |
| Charts | Chart.js 4 |
| Icons | Bootstrap Icons |
| Web Server | Apache (XAMPP) |

---

## Installation

1. Install XAMPP with PHP and MySQL/MariaDB.
2. Clone or copy this repository into the `htdocs` directory.
3. Start Apache and MySQL from the XAMPP Control Panel.
4. Create the required database in phpMyAdmin.
5. Import the database SQL file supplied with the project.
6. Configure the database connection using the project's existing configuration file.
7. Open the application in your browser using the appropriate localhost URL.

**Important:** The database name, SQL filename, and configuration file depend on the actual project files. Check those values in your local project before installation.

---

## Project Structure

```text
SMS/
├── admin/
├── assets/
│   ├── css/
│   └── js/
├── uploads/
├── README.md
└── ...
```

The structure above is illustrative. Actual directories and files may vary.

---

## Security Notes

- Do not commit database passwords, API keys, or other secrets.
- Avoid uploading real student photos or sensitive student information to a public repository.
- Configure database credentials securely before deployment.
- Use HTTPS and appropriate access controls when deploying to a production server.

---

## License

The project is marked as proprietary. Do not assume permission to redistribute or reuse it without authorization.