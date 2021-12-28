### Introduction
**Vue Lumen Starter** offers to you to connect to the **Lumen (PHP Micro-Framework By Laravel)** through the api using **Vue.js**.

### Screenshots
![Screenshot](https://i.imgur.com/TQFdYNI.png)
![Screenshot](https://i.imgur.com/cIIyCD0.png)

### Included
 * Vue Router
 * Vuex
 * Axios
 * Vue Notification
 * Vue I18n
 * Vue Meta
 * Tailwind
 * Font Awesome 5
 * Lumen Form Request
 * JWT

### Features
* Signup
* Login
* Logout
* Multiple Language System
* Auth / Guest Middleware (FrontEnd & BackEnd)
* Cors Middleware
* Authentication with JWT
* Validation (FrontEnd & BackEnd)
* Tailwind Admin & Auth Templates
* Auto-Logout after access token expired
* Auto-Send access token with axios
* Auto-Loader for every request with axios

### Installation
* Make sure you have **npm** and **composer** installed in your machine.
* Clone to your local path.
* Navigate to {PROJECT-PATH}/back where {PROJECT-PATH} is the path where you cloned project.
* Run `copy .env.example .env` and after file `.env` is copied you need to set database credentials into `.env` file.
* Run `composer install` to install dependencies.
* Run `php artisan migrate` and `php artisan jwt:secret`.
* Navigate to {PROJECT-PATH}/front and run `copy .env.example .env`.
* Run: `npm install`.
* Run: `npm run serve`.
