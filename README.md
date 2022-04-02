## About This Directory

This directory has Setup Authentication with JWT, Roles and Permissions with Spatie's plugin for the same.
The process to setup the code is:

- Git Clone the code
- Run "Composer Install"
- Setup .env file using .env.example as base
- Run "php artisan key:generate" - Setup Laravel Secret Key
- Run "php artisan jwt:secret" - Setup JWT Secret Key
- Run "php artisan migrate:fresh --seed" - Migrate the database and seed it with demo User
- Run "php artisan serve" - To Run the server
