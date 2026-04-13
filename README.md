# Car Rental Web Application

## Overview
A full-stack web application for managing car rentals, developed using Django.  
The system allows users to browse available vehicles, create rental bookings, and manage reservations.  
An administrative panel is included for managing cars, users, locations, and rental data.

## Features
- User authentication and account management  
- Car catalog with filtering (brand, fuel type, transmission, etc.)  
- Rental booking system with date-based pricing  
- Pickup and drop-off location management  
- Admin panel for full data control  
- Automated database seeding with realistic test data  

## Technologies
- **Backend:** Django (Python)  
- **Database:** SQLite (default, easily replaceable)  
- **Libraries:** Faker (for generating test data)  
- **Frontend:** Django Templates (HTML/CSS)  

## Setup Instructions
```bash
git clone <repo-url>
cd CarRent/Rent
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py create   # Generates sample data
python manage.py createsuperuser
python manage.py runserver