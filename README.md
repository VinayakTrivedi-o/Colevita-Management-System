# ColViva - Course Management System

ColViva is a client-side course management system designed to streamline and enhance the educational experience for both instructors (Admins) and students (Users). It provides a simple, intuitive interface for managing courses, registrations, and tracking course completion.

The entire application runs in the browser, using `localStorage` to persist data, meaning no backend server is required.

## Features

The system has two distinct roles with different functionalities:

### 👨‍💼 Admin Features

- **Secure Login:** Admins have a dedicated login page.
- **Course Management (CRUD):**
  - **Create:** Post new courses with a title and schedule.
  - **Read:** View a list of all available courses.
  - **Update:** Edit the details of existing courses.
  - **Delete:** Remove courses from the system.

### 🧑‍🎓 User Features

- **Secure Login:** Users have their own login page.
- **View Courses:** Browse a list of all courses posted by the admin.
- **Course Registration:** Register for one or more available courses.
- **Manage Registered Courses:**
  - Mark a registered course as "Completed".
  - Delete a course from their registered list.
- **View History:** See a history of all completed courses.

## Technology Stack

- **Frontend:** HTML5, CSS3, JavaScript
- **Data Storage:** Browser `localStorage` is used to store all course and user data.

## How to Use

1.  **Clone the repository** or download the source code.
2.  Open the `Homepage.html` file in your web browser.
3.  From the homepage, you can navigate to either the Admin or User login pages.

### Login Credentials

Use the following hardcoded credentials to access the dashboards:

#### Admin Login

- **Username:** `admin`
- **Password:** `admin`

#### User Login

- **Username:** `user`
- **Password:** `user`

---

_This project was created as a demonstration of a front-end-only Course Management System._
