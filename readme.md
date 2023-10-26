# Dcat Admin

## Install

run
```shell
composer install
```

After installation, copy a copy of the `.env.example` file and name it `.env`, then run
```shell
php artisan key:generate
```

Then configure the database connection information and run the following command

> There will be a prompt that the folder already exists, just ignore it.

```php
php artisan admin:install
```

Finally run `php artisan serve`. Then open `http://localhost:8000/admin` to access, account `admin`, password `admin`.