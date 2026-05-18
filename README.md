# Event Management System

## Overview
The Event Management System is a Java EE-based web application designed to simplify the process of organizing and managing events. The system enables administrators and users to efficiently handle event scheduling, participant registration, attendance tracking, and reporting.

---

## Features

### Event Creation
- Create and manage events with details such as:
  - Event name
  - Date and time
  - Venue/location
  - Category

### Event Scheduling
- View upcoming events
- Filter events by date and category
- Manage event schedules efficiently

### Participant Management
- Register participants for events
- Track attendance records
- Manage participant details

### Reporting
- Generate reports on:
  - Event statistics
  - Participant registrations
  - Attendance information

### User Roles
- Role-based access control
- Separate functionalities for:
  - Administrators
  - Regular users

---

## Technologies Used

- **Java EE** - Enterprise application framework
- **Servlets** - HTTP request and response handling
- **JSP (JavaServer Pages)** - Dynamic web page rendering
- **JDBC** - Database connectivity
- **MySQL** - Database management system
- **HTML/CSS** - Frontend design
- **Bootstrap** - Responsive UI framework
- **JBoss** - Application server deployment

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/yourusername/event-management-system.git
```

### Set Up the Database

1. Create a MySQL database
2. Import the provided `schema.sql` file

### Configure the Application

Edit the `db.properties` file and update:
- Database URL
- Username
- Password

### Deploy the Application

Deploy the generated WAR file to the JBoss application server.

### Start the Server

Start the JBoss server and open:

```bash
http://localhost:8080/event-management-system
```

---

## Usage

### Admin Dashboard
Administrators can:
- Create and manage events
- View reports
- Manage participants

### User Dashboard
Users can:
- View upcoming events
- Register for events
- Manage participation details

---

## Contributing

To contribute to this project:

1. Fork the repository
2. Create a new branch

```bash
git checkout -b feature/YourFeature
```

3. Commit your changes

```bash
git commit -m "Add new feature"
```

4. Push to GitHub

```bash
git push origin feature/YourFeature
```

5. Create a Pull Request

---

## Contact

For any queries or support, contact:

📧 maddiralabalasivamanikanta@gmail.com
