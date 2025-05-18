
<p align="center">
  <a href="https://laravel.com" target="_blank">
    <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo">
  </a>
</p>

<p align="center">
  <a href="https://github.com/laravel/framework/actions">
    <img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version">
  </a>
  <a href="https://packagist.org/packages/laravel/framework">
    <img src="https://img.shields.io/packagist/l/laravel/framework" alt="License">
  </a>
</p>

## Hotel Management

Laravel based application that lets customers view room facilities, prices, and availability according to their check-in and check-out dates, and book the room of their choice. A full admin panel is created to perform all CRUD operations for managing hotel rooms.

## Technology Stack

- Laravel 10
- Eloquent ORM
- Blade Templates
- Database Migration/Seeding
- Authentication

## Demo

- Reservation  
  ![userside](https://i.ibb.co/Gfgp0Ybq/22.png)

- Dashboard  
  ![dashboard](https://i.ibb.co/tPzqyFNh/11.png)

- ER Diagram 

## Features

**User Side:**

- User authentication.
- Filter all available rooms based on check-in and check-out dates.
- "My Bookings" page to view all bookings.
- Update user profile.
- User input validation.

**Admin Side:**

- Admin login.
- Dashboard for adding a new room, editing room details, and setting the visibility to visible/hidden.
- Display all bookings.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ramezcode1/hotelManagement.git
   ```
2. Navigate to the project directory:
   ```bash
   cd hotelManagement
   ```
3. Copy `.env.example` to `.env` and edit database credentials there.
4. Install dependencies:
   ```bash
   composer install
   ```
5. Generate application key:
   ```bash
   php artisan key:generate
   ```
6. Run migrations and seed the database:
   ```bash
   php artisan migrate --seed
   ```
7. Start the development server:
   ```bash
   php artisan serve
   ```

## Default Accounts

**User Account:**

- Email: user@gmail.com
- Password: Password@1

**Admin Account:**

- Email: admin@gmail.com
- Password: Password@1

## Contact

- 📧 Email: [info@example.com](mailto:info@example.com)
- 💬 WhatsApp: [+972592604393](https://wa.me/972592604393)
