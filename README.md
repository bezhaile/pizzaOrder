# Custom Ordering System

A full ordering platform with cart logic, item customization features, and an admin dashboard.

## Overview

This system provides a structured way for customers to browse items, customize their order, and place it through a clean and responsive interface. It includes an admin dashboard for managing menu items, orders, and customer interactions.

## Features

* Cart system with add, update, and remove actions
* Item customization options
* Checkout flow with order summary
* Admin dashboard for managing items and orders
* Authentication for customers and admins
* API ready structure

## Tech Stack

* Laravel framework
* Blade or Inertia with Vue
* Tailwind CSS
* MySQL 
* Laravel Sanctum API authentication

## Installation

```bash
git clone https://github.com/bezhaile/pizzaOrder.git
cd custom-ordering-system
composer install
npm install
cp .env.example .env
php artisan key:generate
```

Configure your `.env` file, then run:

```bash
php artisan migrate --seed
npm run dev
php artisan serve
```

## License

This project is for learning and demonstration purposes.
