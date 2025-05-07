# 🏥 Clinic Booking System Database

A MySQL-based relational database for managing clinic operations such as appointments, doctors, prescriptions, and medical records.

---

## 1. 🎯 Objective

Design and implement a full-featured relational database for a real-world use case — **Clinic Booking System** — using only **MySQL**.

---

## 2. 📦 Features

- Manage **doctors**, their **departments**, and **specializations**
- Register and maintain **patient** information
- Schedule and track **appointments**
- Store **medical records**, **prescriptions**, and **medications**

---

## 3. 🗃️ Database Entities

The main tables include:

- `departments`
- `specializations`
- `doctors`
- `patients`
- `appointments`
- `medical_records`
- `prescriptions`
- `prescription_details`

---

## 4. 🔗 Relationships

- **One-to-Many** between departments and doctors
- **One-to-Many** between doctors and appointments
- **One-to-Many** between patients and appointments
- **One-to-One** between appointments and medical records
- **One-to-Many** between prescriptions and prescription details

---

## 5. 🧩 Entity-Relationship Diagram (ERD)

![ERD Diagram for Clinic_database](clinic_database.png)

