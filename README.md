# Laravel Backpack Start
The fully installed Laravel Backpack package on a default laravel 5.4 installation

# Packages/Frameworks
- Laravel 5.4 (https://laravel.com/docs/5.4)
- Backpack (https://laravel-backpack.readme.io/docs)

# Requirements
- PHP 7.0+
- MySQL
- Composer
- NodeJS/NPM

# Installation
This Laravel installation includes all required migrations. To install
simply pull the repo and run the following commands from the projects root folder:
- $ composer update
- At this point a .env file should have been generated, set up your configuration settings for mysql in here
- $ php artisan config:cache
- $ php artisan migrate
- $ php artisan key:generate
