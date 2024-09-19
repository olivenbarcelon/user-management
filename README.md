[![GuardRails badge](https://api.guardrails.io/v2/badges/255756?token=ff13f4db148a1c7907a53bda11769076787a9b72a4704e09437417509471896a)](https://dashboard.guardrails.io/gh/olivenbarcelon/repos/255756)
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