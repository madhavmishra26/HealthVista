# HealthVista

**HealthVista** is a healthcare web application developed using the Django framework. This platform enables users to manage their health by providing a simple interface for both patients and doctors.

## Features

- **Home Page**: A welcoming introduction to the HealthVista platform.
- **About Page**: Information about the project and its objectives.
- **Registration Page**: New users can create an account by registering on the platform.
- **Login Page**: Registered users can log in to their accounts.
- **User Dashboard**: 
  - Users can create and manage their profiles by providing their age and location.
  - After profile creation, users can input up to 5 symptoms to receive a diagnosis.
- **Doctor Dashboard**:
  - Doctors can view patient diagnoses and provide drug recommendations or suggest further consultations.
  - Patients can request appointments, and doctors can schedule these appointments by selecting the date and time.

## Database

The project uses a SQL database to store and access user data, patient information, and appointment details, ensuring efficient data management and retrieval.

## Installation

To get started with HealthVista, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Navigate to the project directory:
   cd healthvista
3. Install the required packages:
   pip install -r requirements.txt
4. Set up the XAMPP server:
   Start the XAMPP Control Panel.
   Start the Apache and MySQL services.
5. Apply migrations:
   python manage.py migrate
6. Run the development server:
   python manage.py runserver
