# PlP_Database_Capstone

# 🏥 Clinical Booking System

A relational database system for managing clinic appointments, patients, doctors, and treatments using MySQL.

---

## 📌 Project Description

This project models a clinical booking system using structured SQL. It allows a clinic to manage:

- Patient records
- Doctor profiles and specialties
- Booking and managing appointments
- Recording medical visits and treatments
- Tracking payments

The database uses proper normalization, relationships, and constraints to ensure data integrity and scalability.

---

## 🛠️ Technologies Used

- **Database**: MySQL
- **Diagram Tool**: [dbdiagram.io](https://dbdiagram.io) for ERD generation
- **File**: `clinical_booking_system.sql`

---

## 🧱 Database Schema Overview

### 👨‍⚕️ Tables:
- `Patients` – Stores patient details
- `Doctors` – Stores doctor profiles and specialties
- `Appointments` – Stores scheduled bookings
- `Visits` – Records visit outcomes and diagnoses
- `Payments` – Manages visit-related payments

---

## 🔗 Relationships:
- One patient can have many appointments
- One doctor can handle many appointments
- Each appointment results in one visit
- Each visit may have one payment

---

## 🖼️ Entity Relationship Diagram (ERD)

![Clinical Booking ERD](clinical_booking_erd.png)

---

## 🚀 Getting Started

### Requirements:
- MySQL 8.0+
- MySQL Workbench or any SQL client

### Steps:
1. Clone or download this repo.
2. Open your MySQL client.
3. Run the script `clinical_booking_system.sql` to create the database and tables.

```sql
SOURCE path_to/clinical_booking_system.sql;

