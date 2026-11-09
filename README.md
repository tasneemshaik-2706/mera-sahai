# Mera Sahai

A web platform that connects job seekers, entrepreneurs and companies. It supports networking, internships and access to reliable job opportunities.

**Technologies:** HTML, CSS, Bootstrap, JavaScript, PHP, SQL

## Project structure

```
mera-sahai/
├── index.html      # Landing page (Bootstrap)
├── style.css       # Custom styles
├── script.js       # Client-side validation and job filtering
├── register.php    # Handles sign-up form submissions
├── db.php          # MySQL connection
└── schema.sql      # Database tables
```

## Setup

1. Install XAMPP (or any PHP + MySQL stack) and copy this folder into `htdocs/`.
2. Create the database: import `schema.sql` in phpMyAdmin.
3. Update the credentials in `db.php` if needed.
4. Open `http://localhost/mera-sahai/` in your browser.

## Features

- Sign-up for job seekers, entrepreneurs and companies
- Browse and filter jobs and internships
- Secure password hashing and prepared SQL statements
