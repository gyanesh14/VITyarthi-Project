### Objective

Build a Python command-line application that automates student medical appointment bookings at the campus health centre while eliminating long queues and scheduling conflicts.

---

### Core Requirements

1. **Student Registration**
* Collect student details: *Full Name*, *Registration Number*, *Age* ($15–100$), and *Phone Number* (10 digits).
* Implement input loops to catch invalid data types without program crashes.


2. **Department & Fee Directory**
* Display available clinical departments (General Medicine, Cardiology, Orthopedics, Pediatrics, Dermatology) alongside their respective consultation fees.


3. **Date & Time Slot Selection**
* Validate user-entered appointment dates  against the system clock to prevent past-date bookings.
* Provide fixed time slots 


4. **Double-Booking Prevention**
* Automatically block a time slot if the same department is already booked for that date and time.


5. **Receipt Generation & Master Ledger**
* Assign a unique ID  to each successful booking.
* Print a confirmation receipt and maintain an active list of all appointments for staff review.



---

### Key System Features

* **Language:** Python 3 (Object-Oriented Design)
* **Dependencies:** None (uses built-in datetime, dataclasses, and qtyping modules)
* **Interface:** Interactive command-line menu loop
