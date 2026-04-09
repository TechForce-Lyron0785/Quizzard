# Quizzard

Quizzard is a PHP and MySQL quiz platform for creating tests, assigning them to classes, sharing student credentials, running exams, and reviewing performance from an admin dashboard.

## Overview

The project has two main areas:

- A student-facing flow for login, dashboard access, quiz participation, answer submission, and completion tracking.
- An admin panel for managing classes, importing question sheets, creating tests, assigning students, and reviewing reports.

## Tech Stack

- PHP
- MySQL / MariaDB
- Bootstrap
- jQuery
- FPDF
- SpreadsheetReader

## Project Structure

```text
.
|-- admin/
|-- css/
|-- database/
|-- files/
|-- fonts/
|-- images/
|-- readme_images/
|-- vendor/
|-- brainrot_quiz.xlsx
|-- index.php
|-- README.md
`-- sampleQuizTemplate.xlsx
```

## Local Setup

1. Place the project inside your PHP server directory.
2. Create a MySQL database.
3. Import `database/script.sql` to create the schema.
4. Optionally import `database/sampleData.sql` for demo data.
5. Update `database/config.php` with your database credentials.
6. Open `index.php` for the student portal or `admin/index.php` for the admin panel.

## Database Config

Use `database/config_sample.php` as the reference format:

```php
define("DB_HOST","localhost");
define("DB_UNAME","YOUR_DATABASE_USER_NAME");
define("DB_PASS","YOUR_DATABASE_PASSWORD");
define("DB_DNAME","YOUR_DATABASE_NAME");
```
