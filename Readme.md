# Laravel Stubs

This repository contains some stubs to simplify your life with Laravel.

Is required that your application has L5-Swagger setuped to correct run. If necessary, you can check this repository with all configuration, fully works and video demonstrations:

https://github.com/sr2ds/laravel-9-tutorial

# How to usage

## Download this files to your laravel application 

```
mkdir stubs
cd stubs
git clone https://github.com/sr2ds/laravel-api-stubs .
```

## To generate resource api

```
php artisan make:model -c -f -m --api -R --test Product
```

## Additional configuration - After files generated

1. Is necessary change 3 `//@todo` lines in your tests files generated;
2. Write your attributes in `migrations` and `Model`(fillable and on swagger block) and `Requests`;
3. Create the route on `routes/api.php`
