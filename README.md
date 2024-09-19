# user-management
User Management System

**System Requirements**
* PHP 7.2.34
* Laravel 5.8.*

**Create Laravel Project**
* composer create-project --prefer-dist laravel/laravel project "5.8.*"

**Setup Project**
* composer install

**Run Project**
* php artisan serve

**Run Test**
* vendor/bin/phpunit

**Dependencies**
* Laravel-Modules
    * composer require nwidart/laravel-modules
    * php artisan vendor:publish --provider="Nwidart\Modules\LaravelModulesServiceProvider"
    * composer dump-autoload