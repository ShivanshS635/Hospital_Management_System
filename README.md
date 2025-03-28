﻿# Hospital Management System

A comprehensive desktop application built with Python and Tkinter for managing hospital operations, appointments, and patient records.

## Features

### 1. Multi-User Authentication System
- Separate login interfaces for:
  - Doctors
  - Receptionists/Administrative Staff
- User registration with secure credentials
- Password-protected access

### 2. Administrative Dashboard
- Complete overview of hospital operations
- Real-time updates of appointments
- Easy navigation between different modules

### 3. Doctor Management
- Add/Update/Delete doctor profiles
- Manage doctor specializations
- Track doctor availability
- Set consultation fees
- Maintain doctor contact information

### 4. Patient Management
- Comprehensive patient registration
- Digital patient records
- Medical history tracking
- Contact information management
- Appointment scheduling

### 5. Appointment System
- Schedule new appointments
- View today's appointments
- Search appointment history
- Email notifications for appointments
- Appointment status tracking

### 6. Medical Records
- Digital prescription management
- Treatment history
- Next visit scheduling
- Symptoms tracking
- Medication records

## Technical Details

### Technology Stack
- **Programming Language**: Python 3.x
- **GUI Framework**: Tkinter
- **Database**: SQLite3
- **Email Service**: SMTP

### File Structure
1. **INTRODUCTORYSCREEN.py** - Welcome screen and user type selection
2. **LOGINSCREEN.py** - Main login interface
3. **CREATESCREEN.py** - New user registration
4. **MENUSCREEN.py** - Main application dashboard
5. **DOCTORSCREEN.py** - Doctor's interface
6. **DOCTORLOGINSCREEN.py** - Doctor authentication
7. **DOCTORCREATESCREEN.py** - Doctor registration

### Database Schema
- **createuser** - Administrative user credentials
- **docuser** - Doctor credentials
- **specialization** - Doctor specializations
- **doctor** - Doctor details
- **appointments** - Patient appointments
- **doctor1** - Patient medical records

## Getting Started

### Prerequisites
- Python 3.x installed
- Required Python packages:
  - tkinter
  - sqlite3
  - smtplib

### Installation
1. Clone the repository
2. Install required packages
3. Run INTRODUCTORYSCREEN.py

### Usage Guide

1. **For First-Time Users**:
   - Choose user type (Doctor/Receptionist)
   - Create new account using Sign Up
   - Login with credentials

2. **For Receptionists**:
   - Manage patient registrations
   - Schedule appointments
   - Update patient records
   - View appointment calendar

3. **For Doctors**:
   - View appointed patients
   - Update medical records
   - Prescribe medications
   - Schedule follow-ups

### Security Features
- Password-protected access
- Role-based authentication
- Secure database operations
- Protected patient information

## Email Notifications
The system automatically sends emails for:
- Appointment confirmations
- Follow-up reminders
- Prescription details
- Next visit schedules

## Interface Guide

### Main Screens
1. **Welcome Screen**:
   - User type selection
   - Professional interface

2. **Dashboard**:
   - Quick access menu
   - Real-time updates
   - Navigation panel

3. **Patient Management**:
   - Registration form
   - Search functionality
   - Record updates

4. **Doctor Interface**:
   - Patient queue
   - Medical records
   - Prescription management

## Future Enhancements
1. Mobile application integration
2. Online appointment booking
3. Digital payment system
4. Medical report generation
5. Inventory management
6. Staff management module

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Support
For support or queries, please contact: shivansh3375@gmail.com

## Acknowledgments
- Python community
- Tkinter documentation
- SQLite documentation
- Healthcare management systems
