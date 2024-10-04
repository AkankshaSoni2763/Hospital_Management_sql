# Hospital Management System

## Introduction
The **Hospital Management System** is a database-driven application that helps manage patient records, doctor schedules, medical histories, appointments, and diagnoses. The system is designed to streamline hospital operations and facilitate the management of healthcare services.

## Features
- Patient registration and management
- Doctor schedules and appointments
- Medical history tracking
- Diagnoses and prescriptions management
- Patient visits and concerns tracking
- Doctor access to patient medical history

## Technologies Used
- **Database**: PostgreSQL (or any other SQL-based DBMS)
- **Schema**: `hospital_management`
- **Languages**: SQL
- **Tools**: Any SQL client (e.g., pgAdmin, MySQL Workbench)

## Database Structure
The database consists of several interconnected tables within the `hospital_management` schema. The key entities include:
- **`patient`**: Stores patient details.
- **`doctor`**: Contains doctor information.
- **`medical_history`**: Manages patients' past medical conditions, surgeries, and medications.
- **`appointment`**: Handles appointment details.
- **`diagnose`**: Stores diagnosis and prescription information.
- **`schedule`**: Manages doctor schedules.
- **`patient_visits`**: Tracks patient appointments, concerns, and symptoms.
- **`doctor_view_history`**: Tracks which doctor has viewed which patient's medical history.



## Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/hospital-management-system.git
   cd hospital-management-system

## Usage
Once the database is set up, you can interact with it using SQL queries to:

- Register new patients and doctors.
- Create appointments.
- Add medical history records.
- View and update patient visits.
- Manage doctor schedules.

