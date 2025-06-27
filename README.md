# 🏥 Hospital Management System

## 📖 Overview

The **Hospital Management System** is a comprehensive desktop application built using **Java (NetBeans)** and **MySQL** to streamline hospital operations. This system ensures efficient handling of:
- 👨‍⚕️ Doctor information
- 🧑‍🤝‍🧑 Patient records
- 👩‍💼 Receptionist and staff data
- 🔐 User authentication for admin and users

This project integrates a structured database with a clean Java UI and is suitable for hospitals, clinics, or academic demonstrations.

---

## 🚀 Features

✨ **Authentication System**
- Secure admin login (`admin/admin`)
- Additional user login credentials

🩺 **Doctor Management**
- Register and manage doctor details
- View qualifications, contact info, and availability

🧑‍⚕️ **Patient Records**
- Add, update, and view patient history
- Capture vital details: address, mobile, age, city, etc.

👨‍💼 **Receptionist & Worker Management**
- Maintain profiles of front desk and support staff

📂 **Database Integration**
- Relational tables designed for real-world hospital workflow
- Includes realistic dummy data for demonstration

📦 **Build & Run (Ant Script)**
- Uses `build.xml` for compiling and running via Apache Ant
- Easy integration with NetBeans IDE

---

## 🛠️ Tech Stack

| Component     | Technology         |
|---------------|--------------------|
| 👨‍💻 Language       | Java              |
| 🧱 Framework     | NetBeans IDE       |
| 🗄️ Database      | MySQL              |
| ⚙️ Build Tool    | Apache Ant         |

---

## 📁 Project Structure

    HospitalManagementSystem/
    ├── build.xml # Ant build script
    ├── nbproject/ # NetBeans project configs
    ├── src/ # Java source files
    ├── hospital.sql # SQL dump for database setup
## 🔐 Sample Login Credentials
| Role  | Username | Password |
| ----- | -------- | -------- |
| Admin | admin    | admin    |
| User  | 1234     | 1234     |
## 🧠 Additional Notes
- The SQL dump includes comprehensive data for all major modules.
- Tables are normalized for performance and scalability.
- build.xml contains hooks to extend the build process if needed (e.g., for obfuscation, packaging .jar, etc.)
