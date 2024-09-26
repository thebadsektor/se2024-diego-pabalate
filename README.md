# SD-3101 [Pet Grooming Appoint System]
Introduction
The Open Source Pet Grooming Appointment System is a web-based project developed using PHP, HTML, and CSS. This system facilitates online appointment scheduling for clients seeking pet grooming services. It helps pet groomers manage appointments and organize schedules efficiently. The system supports three main roles: administrator, groomer, and client.

**Project Overview**
The system allows administrators to manage groomer profiles and their schedules, groomers to view and manage their appointments, and clients to book and manage their grooming appointments online.

**Features**

**Admin**
Add, edit, and delete groomers
Schedule and remove grooming sessions
View client details
View client bookings

**Groomers**
View their appointments
View their scheduled grooming sessions
View client details
Delete or edit their account settings

**Clients**
Make grooming appointments online
Create and manage their accounts
View past bookings
Delete or edit their account settings

Admin Dashboard      Groomer Dashboard       Client Dashboard

Email: admin@petgroom.com	       Email: groomer@petgroom.com	| Email: client@petgroom.com	
Password: 123 Password: 123Password: 123

		
**Setup and Installation**
1. Clone the repository:
   git clone https://github.com/HashenUdara/edoc-doctor-appointment-system.git

2. Open your XAMPP Control Panel and start Apache and MySQL.
3. Extract the downloaded source code zip file.
4. Copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory.
5. Open PHPMyAdmin in a browser: http://localhost/phpmyadmin
6. Create a new database named edoc.
7. Import the provided SQL file (edoc.sql) located in the source code root folder.
8.  Open the Pet Grooming Appointment System in a browser: http://localhost/pet-grooming-system/
			
**Screenshots** 

			
Technologies Used
Apache Version: 2.4.39
PHP Version: 7.3.5
MySQL Version: 5.7.26
Server Software: Apache/2.4.39 (Win64) PHP/7.3.5

**Changelog**

6 months ago - Initial release

**Project Structurers**
```
appointment/
├─ admin/
│  ├─ add-new.php
│  ├─ add-session.php
│  ├─ appointment.php
│  ├─ delete-appointment.php
│  ├─ delete-doctor.php
│  ├─ delete-session.php
│  ├─ doctors.php
│  ├─ edit-doc.php
│  ├─ index.php
│  ├─ patient.php
│  ├─ schedule.php
├─ css/
│  ├─ fonts/
│  │  ├─ admin.css
│  │  ├─ animations.css
│  │  ├─ font-inter.css
│  │  ├─ index.css
│  │  ├─ login.css
│  │  ├─ main.css
│  │  ├─ patient.css
│  │  ├─ signup.css
├─ doctor/
│  ├─ appointment.php
│  ├─ delete-appointment.php
│  ├─ delete-session.php
│  ├─ doctors.php
│  ├─ edit-doc.php
│  ├─ index.php
│  ├─ patient.php
│  ├─ schedule.php
│  ├─ settings.php
├─ img/
├─ patient/
│  ├─ appointment.php
│  ├─ booking-complete.php
│  ├─ booking.php
│  ├─ delete-account.php
│  ├─ delete-appointment.php
│  ├─ doctors.php
│  ├─ edit-user.php
│  ├─ index.php
│  ├─ patient.php
│  ├─ schedule.php
│  ├─ settings.php
├─ connection.php
├─ create-account.php
├─ image.png
├─ index.html
├─ LICENSE
├─ login.php
├─ logout.php
├─ README.md
├─ SECURITY.md
├─ signup.php
├─ SQL-Database_edoc.sql
```

**Contributors**
Jim Dominic Pabalate - Initial development

**Acknowledgments**
- hashenudara


**License**
This project is licensed under the MIT License - see the LICENSE file for details.
