<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About this repo
A quick showcase and test of a simple user authentication workflow utilizing Laravel Jetstream's Inertia. Here is the tech stack utilized specifically:
- Laravel
- Laravel Jetstream
- Inertia
- Vue.js
- MySQL

## How to run?
This app follows Laravel's Jetstream and Inertia's out-of-the-box getting started documentation, so feel free to refer to the stated page for reference should you run into any trouble.

1. Please make sure you have composer and Laravel installed in your system. Then, simply clone the GitHub repo to your local directory.

2. Run `npm install` to install Node dependencies.

3. Run `npm run dev` to initialize Vue.js instance.

4. Check `.env` and its subsequent MySQL configuration line.

          DB_CONNECTION=mysql
          DB_HOST=127.0.0.1
          DB_PORT=3306
          DB_DATABASE=<your_database>
          DB_USERNAME=root
          DB_PASSWORD=<your_password>

5. Run `php artisan merge`, given you have MySQL running on your system. 

6. Run `php artisan serve` to run the development server.