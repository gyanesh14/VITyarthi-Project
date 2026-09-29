# VIT Bhopal Health Centre - Appointment Booking System

A Python-based command-line interface (CLI) application developed to streamline patient registration, department selection, and slot booking at the VIT Bhopal Health Centre.

---

## Features

- **Student Registration**: Captures key student details including Name, Registration Number, Age, and Contact Number with built-in input validation.
- **Department & Fee Selection**: Allows students to choose from multiple clinical departments:
  - General Medicine (₹500)
  - Cardiology (₹1000)
  - Orthopedics (₹800)
  - Pediatrics (₹600)
  - Dermatology (₹900)
- **Date & Time Slot Scheduling**:
  - Validates date inputs (`DD-MM-YYYY`) and prevents booking for past dates.
  - Offers standard appointment slots ranging from 9:00 AM to 4:00 PM.
- **Appointment Summary & Tracking**: Automatically generates a unique Appointment ID (e.g., `APT1001`) and outputs a full appointment slip.
- **Appointment Records**: Enables users to view all booked appointments during the current session.

---

# Project Structure

  ``text
  ├── code.py         ## Main application script
  ├── README.md       # Project documentation
  └── statement.md    # Problem statement and system specifications


### Prerequisites
- Python 3.7+ installed on your system.

- Standard Python libraries (datetime is built-in; no external pip installations required).

## How to Run in VS Code
- Open the project folder in VS Code (File > Open Folder...).
- Open the built-in terminal (Ctrl + ~ on Windows/Linux or Cmd + ~ on macOS).
- Run the script using Python:
  python code.py
