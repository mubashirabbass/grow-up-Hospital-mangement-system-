
# 🏥 Grow-Up Hospital Management System

A modern, feature-rich desktop application built using **Python (Tkinter)** and **MySQL**, designed to manage hospital operations including patient registration, doctor and staff management, user authentication, appointment tracking, and reporting — all with a modern animated UI experience.

## 🚀 Features

* 🌐 Multi-role login system (Admin, Doctor, Patient, Staff)
* 💾 MySQL database integration with secure hashed passwords
* 🧾 Patient registration and profile management
* 👨‍⚕️ Doctor and staff management dashboards (add/edit/delete)
* 📅 Appointment and billing modules
* 📊 Dynamic admin dashboard with real-time statistics
* 🎞️ Animated loading and welcome screens using GIFs
* 📤 Export to PDF, Excel for reports and data
* 🖼️ User profile picture handling and uploads
* 🔐 Encrypted password storage using SHA256
* 🪟 Clean GUI with modern visuals and user experience

## 🛠️ Technologies Used

* **Python 3.x**
* **Tkinter** – GUI framework
* **MySQL** – Relational database
* **Pillow** – Image handling
* **ReportLab** – PDF generation
* **OpenPyXL** – Excel report creation
* **Tkcalendar** – Calendar input
* **Logging** – Error and debug logging

## 📂 How to Run

1. **Install Requirements:**

```bash
pip install pillow mysql-connector-python reportlab openpyxl tkcalendar
```

2. **Set up MySQL Database:**

   * Create a database named `hospital_management_system`.
   * Import tables (Users, Patients, Doctors, Staff, Appointments, etc.).
   * Update database credentials in the code:

     ```python
     host="localhost",
     user="root",
     password="",
     database="hospital_management_system"
     ```

3. **Place Assets:**

   * Required GIFs and images: `heart2.gif`, `hospital.gif`, `admin_logo.png`, `doctor_logo.png`, `patient_logo.png`, `staff_logo.png`, etc.
   * Place them in the same directory as your Python script.

4. **Run the Application:**

```bash
python code file.py
```


## 🙌 Acknowledgments

Developed by **Mubashir Abbas**
💼 BS Software Engineering, GCUF (Government College University Faisalabad)

Screenshots 
<img width="684" alt="main animation loading screen" src="https://github.com/user-attachments/assets/374208e5-5a80-4fce-abb9-c62fbdfce635" />
<img width="635" alt="login roles" src="https://github.com/user-attachments/assets/55133a96-530e-4edf-a3a8-7ecde3232808" />
<img width="597" alt="login menu" src="https://github.com/user-attachments/assets/c542bbe9-1f62-4929-8799-7a6cede20c04" />
<img width="869" alt="admin dashboard" src="https://github.com/user-attachments/assets/e1cbcf50-15d3-48ef-baf8-3b2fbdc73383" />
<img width="853" alt="staff dashboard" src="https://github.com/user-attachments/assets/f68234fd-abb6-4ebe-8c20-f8b67436bd49" />
<img width="859" alt="patient dahboard" src="https://github.com/user-attachments/assets/4f768b44-7c53-4add-a301-785775f8ebd5" />
<img width="871" alt="doctors dashboard" src="https://github.com/user-attachments/assets/d002e9b3-2617-4439-80fd-61a45b5ff6dc" />


