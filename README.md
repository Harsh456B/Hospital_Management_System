# Hospital_Management_System

## Project Description

The Hospital Management System is a web-based application designed to streamline the management of hospital operations, including patient registration, doctor management, appointments, billing, and more. Built using Django, this system provides an intuitive interface for administrators, doctors, and patients to interact efficiently.

## Features

- **Admin Dashboard:** Manage doctors, patients, appointments, and view statistics.
- **Doctor Management:** Add, approve, update, and view doctor details.
- **Patient Management:** Register, approve, update, and view patient details.
- **Appointment Scheduling:** Book, approve, and manage appointments between doctors and patients.
- **Billing & Discharge:** Generate and download patient bills, manage discharge details.
- **Authentication:** Secure login/signup for admin, doctors, and patients.
- **Responsive UI:** User-friendly interface for all user roles.

## Technologies Used

- Python 3.x
- Django
- HTML, CSS (Bootstrap)
- SQLite (default Django database)
- JavaScript (for interactivity)

## Setup Instructions

1. **Clone the Repository**
   ```sh
   git clone https://github.com/Harsh456B/Hospital_Management_System.git
   cd Hospital_Management_System
   ```

2. **Create a Virtual Environment**
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```sh
   pip install django
   ```

4. **Apply Migrations**
   ```sh
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Create a Superuser (Admin)**
   ```sh
   python manage.py createsuperuser
   ```

6. **Run the Development Server**
   ```sh
   python manage.py runserver
   ```

7. **Access the Application**
   - Open your browser and go to: `http://127.0.0.1:8000/`

## Usage

- **Admin:** Can log in to the admin dashboard, manage doctors, patients, and appointments.
- **Doctor:** Can view appointments, manage patient details, and update their profile.
- **Patient:** Can book appointments, view doctors, and manage their profile.

## Folder Structure

- `hospital/` - Main Django app with models, views, forms, and migrations.
- `hospitalmanagement/` - Project settings and configuration.
- `static/` - Static files (CSS, images, etc.).
- `templates/` - HTML templates for all user interfaces.

## Screenshots

_Add screenshots from the `static/screenshots/` folder here to showcase the UI._

## License

This project is licensed under the MIT License.
