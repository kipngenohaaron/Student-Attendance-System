
# **Student Attendance System (Django)**

A complete **Student Attendance Management System** built using **Python (Django Framework)** for educational and administrative purposes.
This system helps institutions efficiently manage students, staff, courses, and attendance records in a centralized platform.

> ⭐ If you find this project useful, please consider giving it a **Star** on GitHub!

---

## 📑 **Table of Contents**

1. [Overview](#-overview)
2. [Key Features](#-key-features)

   * [Admin (HOD)](#a-admin-head-of-department)
   * [Staff / Teachers](#b-staff--teachers)
   * [Students](#c-students)
3. [Installation & Setup](#-installation--setup)

   * [Prerequisites](#prerequisites)
   * [Create and Activate Virtual Environment](#step-1-create-and-activate-a-virtual-environment)
   * [Clone the Project](#step-2-clone-the-project)
   * [Install Dependencies](#step-3-install-dependencies)
   * [Configure Allowed Hosts](#step-4-configure-allowed-hosts)
   * [Set Up the Database](#step-5-set-up-the-database)
   * [Run the Server](#step-6-run-the-server)
4. [Default Login Credentials](#-default-login-credentials)
5. [Developer Information](#-developer-information)
6. [License](#-license)

---

## 📘 **Overview**

The **Student Attendance System** is designed to simplify student and staff management for schools, colleges, and universities.
It enables automated attendance tracking, performance monitoring, and communication between students, staff, and administrators — all from a single web interface.

---

## 🚀 **Key Features**

### **A. Admin (Head of Department)**

1. View overall performance dashboards for students, staff, courses, and attendance.
2. Manage **staff**, **students**, **courses**, **subjects**, and **sessions** (add, update, or delete).
3. View and monitor **attendance reports**.
4. Review and respond to **feedback** from staff and students.
5. Approve or reject **leave requests** submitted by staff or students.

---

### **B. Staff / Teachers**

1. Access summary dashboards related to assigned subjects and attendance.
2. Record or update **student attendance**.
3. Add or update **student results**.
4. Apply for **leave**.
5. Send **feedback** to the HOD/admin.

---

### **C. Students**

1. View personal **attendance reports** and **results**.
2. Access **subjects**, **session information**, and **leave status**.
3. Apply for **leave**.
4. Send **feedback** to the HOD/admin.

---

## 🧰 **Installation & Setup**

### **Prerequisites**

Ensure you have the following installed:

* [Git](https://git-scm.com/)
* [Python (latest version)](https://www.python.org/downloads/)
* [Pip (Python package manager)](https://pip.pypa.io/en/stable/installing/)

> 💡 *Alternative to Pip (Mac users):* [Homebrew](https://brew.sh/)

---

### **Step 1: Create and Activate a Virtual Environment**

Install `virtualenv`:

```bash
pip install virtualenv
```

Create a virtual environment:

**Windows:**

```bash
python -m venv venv
```

**Mac/Linux:**

```bash
python3 -m venv venv
```

Activate the environment:

**Windows:**

```bash
venv\Scripts\activate
```

**Mac/Linux:**

```bash
source venv/bin/activate
```

---

### **Step 2: Clone the Project**

```bash
git clone https://github.com/kipngenohaaron/Student-Attendance-System.git
cd Student-Attendance-System
```

---

### **Step 3: Install Dependencies**

```bash
pip install -r requirements.txt
```

---

### **Step 4: Configure Allowed Hosts**

In the project’s `settings.py`, update:

```python
ALLOWED_HOSTS = ['*']
```

*(This allows local development and testing.)*

---

### **Step 5: Set Up the Database**

Run database migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

Then create an admin user (HOD):

```bash
python manage.py createsuperuser
```

Enter your preferred email, username, and password.

---

### **Step 6: Run the Server**

**Windows:**

```bash
python manage.py runserver
```

**Mac/Linux:**

```bash
python3 manage.py runserver
```

Access the app in your browser:
👉 `http://127.0.0.1:8000/`

---

## 🔐 **Default Login Credentials**

| Role        | Email                                         | Password |
| ----------- | --------------------------------------------- | -------- |
| HOD / Admin | [admin@gmail.com](mailto:admin@gmail.com)     | admin    |
| Staff       | [staff@gmail.com](mailto:staff@gmail.com)     | staff    |
| Student     | [student@gmail.com](mailto:student@gmail.com) | student  |

---

## 👨‍💻 **Developer Information**

**Name:** Kipngenoh Aaron Rotich
**Email:** [kipngenohaaron@gmail.com](mailto:kipngenohaaron@gmail.com)
**Phone:** 0724 828 197 / 0724 279 400
**GitHub:** [@kipngenohaaron](https://github.com/kipngenohaaron)

---

## ⚖️ **License**

MIT License © 2025 **Kipngenoh Aaron Rotich**
Permission is granted, free of charge, to use, copy, modify, and distribute this software for educational and personal use.
The software is provided **“as is”**, without warranty of any kind.


