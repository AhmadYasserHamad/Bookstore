# Bookstore

A modern web application for managing and browsing a bookstore, built with the [Laravel](https://laravel.com/) PHP framework. 

This repository houses the application's backend logic, frontend assets, and system architecture planning. 

## Features (Planned/Implemented)
* **User Authentication:** Secure registration, login, and session management.
* **Book Catalog:** Browse books by category, author, or search by title.
* **Shopping Cart & Checkout:** Seamless user experience for adding books and processing orders.
* **Admin Dashboard:** Interface for administrators to manage inventory, update book details, and track incoming orders.
* **System Architecture:** Detailed database and system designs (viewable in the `Diagrams/` directory).

## Tech Stack
* **Backend:** PHP, Laravel
* **Frontend:** Blade Templates, HTML/CSS/JavaScript (bundled via Vite)
* **Database:** MySQL / PostgreSQL / SQLite
* **Dependency Management:** Composer, NPM

## Prerequisites
Ensure your local development environment meets the following requirements:
* [PHP](https://www.php.net/) >= 8.1
* [Composer](https://getcomposer.org/)
* [Node.js & NPM](https://nodejs.org/)
* A supported relational database

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/AhmadYasserHamad/Bookstore.git](https://github.com/AhmadYasserHamad/Bookstore.git)
   cd Bookstore
2. **Install PHP dependencies:**
   ```bash
   composer install
3. **Install and compile frontend dependencies:**
   ```bash
   npm install
   npm run build
4. **Environment Configuration**
   ```bash
   cp .env.example .env
5. **Generate the Application Key:**
   ```bash
   php artisan key:generate
6. **Run Database Migrations:**
   ```bash
   php artisan migrate
7. **Start the Development Server:**
   ```bash
   php artisan serve
## Key Directory Structure
• app/: Contains the core logic, including Controllers and Eloquent Models.
• database/: Houses database migrations, factories, and seeders.
• resources/: Contains all Blade view templates and uncompiled raw assets.
• routes/: Defines the web and API routing for the application.
• Diagrams/: Contains project architecture documentation and Entity-Relationship Diagrams (ERDs).
