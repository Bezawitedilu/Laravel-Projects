# **Laravel Projects**

# Project 1

# Attendance Management System Dashboard

## Introduction
This is an Attendance Management System Dashboard built using Laravel. The system is designed to help organizations efficiently manage the attendance of their employees. It provides a user-friendly dashboard interface for administrators to monitor attendance records, generate reports, and manage employee information.

## Features
- **User Authentication**: Secure login system for administrators.
- **Employee Management**: CRUD operations for managing employee information.
- **Attendance Tracking**: Record and manage attendance data for each employee.
- **Dashboard**: Visual representation of attendance statistics and trends.
- **Reports**: Generate detailed reports on attendance data for analysis.
- **Settings**: Customizable settings for system configurations.

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/Bezawitedilu/Laravel-Projects.git
        ```
2. Navigate to the project directory:
    ```bash
    cd attendance-management-system
    ```
3. Install dependencies via Composer:
    ```bash
    composer install
    ```
4. Copy the `.env.example` file to `.env` and configure your database settings:
    ```bash
    cp .env.example .env
    ```
5. Generate application key:
    ```bash
    php artisan key:generate
    ```
6. Migrate the database:
    ```bash
    php artisan migrate
    ```
7. (Optional) Seed the database with sample data:
    ```bash
    php artisan db:seed
    ```
8. Serve the application:
    ```bash
    php artisan serve
    ```

## Usage
1. Access the application through your web browser.
2. Log in with the provided administrator credentials.
3. Navigate through the dashboard to manage employees, record attendance, generate reports, and configure settings.

## Contributors
- Bezawit Liro bezawitedilu@gmail.com

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Laravel - The PHP framework used.
- Bootstrap - Frontend framework for styling.

---


