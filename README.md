# IT Helpdesk and Ticketing System

A Flask-based Smart IT Helpdesk and Ticketing System developed to streamline customer support operations through ticket management, authentication, issue tracking, and Jira integration. The system enables users to create, manage, and track support tickets efficiently while providing a centralized workflow for IT support operations.

This project demonstrates core concepts of backend web development, database management, REST APIs, authentication systems, and support ticket lifecycle management using Python Flask and MySQL.

---

# Features

## Authentication Module
- User Registration (Signup)
- User Login
- Session Management
- User Profile Management

## Ticket Management Module
- Create New Support Tickets
- View Existing Tickets
- Track Ticket Status
- Display Detailed Ticket Information
- Manage Ticket Workflow

## Jira Integration
- Create Jira Issues Automatically
- Integrate Ticket Information with Jira
- Streamline Issue Tracking Process

## Database Management
- MySQL Database Integration
- SQLAlchemy ORM Usage
- Client and Ticket Data Management

## User Interface
- Responsive HTML Templates
- Clean Navigation Structure
- Form-based Ticket Submission
- Organized Ticket Display Pages

---

# Technologies Used

## Backend
- Python
- Flask Framework

## Database
- MySQL
- SQLAlchemy ORM

## Frontend
- HTML5
- CSS3
- Bootstrap

## APIs & Integrations
- RESTful APIs
- Jira API Integration

---

# Project Structure

```bash
smart-it-helpdesk-system/
│
├── .gitignore
├── __init__.py
├── auth.py
├── db.sql
├── exceptions.py
├── jira_actions.py
├── main.py
├── model.py
├── README.md
├── requirements.txt
├── ticket.py
│
├── static/
│
├── templates/
│   ├── base.html
│   ├── index.html
│   ├── signup.html
│   ├── login.html
│   ├── profile.html
│   ├── ticket_form.html
│   ├── show_all_ticket.html
│   └── show_ticket.html
│
└── Report/
```

---

# File Description

## main.py
Acts as the main entry point of the application. It handles application initialization, routing configuration, and overall project orchestration.

## auth.py
Handles authentication-related functionalities including:
- Signup
- Login
- Session Management
- User Validation

## model.py
Defines database models and manages relationships between entities such as clients and tickets.

## ticket.py
Contains all ticket-related operations including:
- Ticket Creation
- Ticket Retrieval
- Ticket Updates
- Ticket Display

## jira_actions.py
Implements Jira integration functionalities and allows interaction with Jira for issue tracking and management.

## exceptions.py
Contains custom exception handling logic to improve application stability and debugging.

## db.sql
Database schema file used for creating and configuring MySQL tables required by the application.

## templates/
Contains all HTML templates used for rendering frontend pages.

## static/
Contains static resources such as:
- CSS files
- JavaScript files
- Images

---

# Functional Modules

## Authentication System
The authentication system allows users to securely register and log into the platform using credentials. Session handling ensures protected access to authorized pages.

### Functionalities
- User Signup
- User Login
- User Session Handling
- Profile Management

---

## Ticket Management System
The ticket management module enables users to create, view, and manage support tickets efficiently.

### Functionalities
- Raise New Ticket
- View All Tickets
- Track Ticket Status
- View Ticket Details
- Ticket Workflow Handling

---

## Jira Integration System
This module allows automatic creation and management of Jira issues corresponding to support tickets.

### Functionalities
- Jira Issue Creation
- Jira Ticket Synchronization
- Issue Tracking Support

---

## Database System
The database layer stores customer information and ticket records using MySQL and SQLAlchemy ORM.

### Database Tables
- Client Table
- Ticket Table

---

# Workflow of the System

1. User enters customer ID or phone number.
2. System checks whether the customer exists in the database.
3. If the customer is new, registration is performed.
4. Existing users can create support tickets.
5. Ticket information is stored in the database.
6. Jira issue is automatically created.
7. User receives Ticket ID for future tracking.
8. Tickets can be viewed and managed through the system.

---

# User Interface Pages

| HTML File | Purpose |
|------------|---------|
| base.html | Common layout template |
| index.html | Homepage |
| signup.html | User registration page |
| login.html | User login page |
| profile.html | User profile page |
| ticket_form.html | Ticket creation form |
| show_all_ticket.html | Display all tickets |
| show_ticket.html | Detailed ticket information |

---

# Installation Guide

## Step 1: Clone Repository

```bash
git clone https://github.com/your-username/smart-it-helpdesk-system.git
```

---

## Step 2: Navigate to Project Folder

```bash
cd smart-it-helpdesk-system
```

---

## Step 3: Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## Step 4: Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Step 5: Configure Database

- Create a MySQL database
- Import the `db.sql` file
- Configure database credentials inside the application

---

## Step 6: Run the Application

```bash
python main.py
```

---

# Key Concepts Implemented

- Flask Routing
- Authentication Systems
- Session Management
- CRUD Operations
- RESTful APIs
- SQLAlchemy ORM
- MySQL Database Integration
- Jira API Integration
- Error Handling
- Template Rendering

---

# Future Enhancements

The following features can be added in future versions:

- Admin Dashboard
- Ticket Priority Levels
- Email Notifications
- Role-Based Access Control
- Real-Time Ticket Tracking
- System Monitoring Dashboard
- Network Diagnostics Module
- Ticket Analytics Dashboard
- Chat Support Integration

---

# Screenshots

## Homepage
(Add Homepage Screenshot Here)

## Login Page
(Add Login Page Screenshot Here)

## Ticket Creation Page
(Add Ticket Form Screenshot Here)

## Ticket Dashboard
(Add Dashboard Screenshot Here)

---

# Learning Outcomes

This project helped in understanding:

- Backend Web Development using Flask
- Authentication and Session Handling
- Database Design and ORM Integration
- CRUD-based Application Development
- Jira API Integration
- Ticket Lifecycle Management
- Error Handling and Exception Management
- Frontend and Backend Integration

---

# Disclaimer

This project was customized and enhanced for learning and portfolio purposes to demonstrate IT helpdesk workflow, support ticket lifecycle management, authentication systems, and issue tracking concepts.

---

# Author

Sinchana
