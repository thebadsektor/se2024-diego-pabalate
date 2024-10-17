# SD-3101 [Pet Grooming Appoint System]
## Table of Contents
- [Introduction](#introduction)
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage Instructions](#usage-instructions)
- [Project Structure](#project-structure)
- [Contributors](#contributors)
- [Chagelog](#changelog)
- [Acknowledgments](#acknowledgments)
- [License](#license)



## Introduction
The Open Source Pet Grooming Appointment System is a web-based project developed using PHP, HTML, and CSS. This system facilitates online appointment scheduling for clients seeking pet grooming services. It helps pet groomers manage appointments and organize schedules efficiently. The system supports three main roles: administrator, groomer, and client.

## Project Overview
The system allows administrators to manage groomer profiles and their schedules, groomers to view and manage their appointments, and clients to book and manage their grooming appointments online.

## Objectives
The main objectives of the Pet Grooming Appointment System capstone project are to:

- Develop a solution for efficiently managing pet grooming appointments to improve the booking experience for clients and streamline scheduling for groomers and administrators.
- Implement core features to support different user roles, including administrators, groomers, and clients, to allow for seamless account management, appointment scheduling, and personalized dashboards.
- Test and validate the system’s performance, usability, and security to ensure a reliable and user-friendly experience for both clients and grooming professionals.


## Features

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

## Technologies Used

- Programming language: PHP
- Frameworks/Libraries: none
- DatabasesL Mysql
- Other tools: xammp
		
## Setup and Installation
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

## Usage Instructions

## Project Structurers
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

## Contributors

List all the team members involved in the project. Include their roles and responsibilities:

- **[Jim Dominic Pabalate]**: Lead Developer, Backend Developer
- **[Julius Diego]**: Frontend Developer, UI/UX Designer
- **Gerald Villaran**: Project Manager, Tester

## Project Timeline

Outline the project timeline, including milestones or deliverables. Example:

- **Week 1-2**: Collaborative brain storming for features development
  	- 09/15/2024
  	- https://youtu.be/sOAkmxdDW8A
  	- Proposed Features
  	  	- Grooming history
  	  	- Automated reminders
		- Custom grooming packages
		- Pet profiles
		- Real-time updates
		- Online payments
		- Loyalty rewards
		- Groomer ratings
		- Pickup/drop-off tracking
		- Groomer portfolio
  	  
- **Week 3-5**: Design and setup.
- **Week 6-10**: Implementation.
- **Week 11-12**: Testing and debugging.
- **Week 13-14**: Final presentation and documentation.

## Changelog

### [Version 1.0.0] - 2024-09-07
- Initial release of the project.
- Added basic functionality for [Feature 1], [Feature 2], and [Feature 3].

### [Version 1.1.0] - 2024-09-14
- Improved user interface for [Feature 1].
- Fixed bugs related to [Feature 2].
- Updated project documentation with setup instructions.

### [Version 1.2.0] - 2024-09-21
- Added new functionality for [Feature 4].
- Refactored codebase for better performance.
- Added unit tests for [Feature 3] and [Feature 4].


## Acknowledgments

Acknowledge any resources, mentors, or external tools that helped in completing the project.

This project was built from [Original Project Name](https://github.com/username/original-repo), created by [hashenudara]. You can view the original repository [here](https://github.com/username/original-repo).

## License
This project is licensed under the MIT License - see the LICENSE file for details.
