# Blog Management Flask Project

## Overview

This Flask project is designed to provide Blog and User management functionalities with a focus on security, flexibility, and maintainability. Below are the key features and design principles incorporated into the project.

## Features

### 1. Signup and Login
- Users can sign up and create an account.
- Authentication is implemented for user logins.

### 2. User Verification
- User status must be verified for successful login, ensuring a secure authentication process.

### 3. Send Mail Functionality
- Utilizes SendGrid for sending system emails.
- Easily customizable to add other email services as needed.

### 4. Blogs management
- Utilized CRUD of blogs with modularized functions and methods

### 5. Asynchronous Tasks with Celery
- Celery is integrated for handling asynchronous tasks, improving performance and responsiveness.

### 6. Logging Services
- Implemented logging for various log levels: debug, info, warning, error.
- Custom attributes are logged with a JSON formatter for improved readability.

### 7. Exception Handling
- Exceptions are appropriately handled to ensure smooth execution and enhance user experience.

### 8. Domain Driven Design (DDD)
- Utilizes Domain Driven Design principles for organizing project structure, promoting modularization and maintainability.

### 9. Loosely Coupled Models
- The project embraces a loosely coupled model design, enhancing flexibility and ease of maintenance.

### 10. Utility Service
- Includes a utility service for common project requirements, promoting code reusability.

### 11. Data Classes for Model Abstraction
- Implemented data classes for model abstraction, improving code readability and maintainability.


## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/rachit-patel-dev/flask-work-sample.git
   cd user_management_project
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure Django settings in `settings.py`, including database settings, email service API keys, and other project-specific configurations.

4. Start the development server:

   ```bash
   python config.py
   ```

6. Access the application at `http://localhost:5000/`.