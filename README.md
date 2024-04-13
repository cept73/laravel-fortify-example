# Laravel 11 Fortify Example
Laravel 11 Authentication Scaffold using Laravel Fortify and Bootstrap.


## Video Tutorials
1. [Authentication Scaffolding Using Laravel Fortify](https://www.youtube.com/watch?v=CLsyHP7x0N0)
2. [Forget Password & User Profile Update with Laravel Fortify](https://www.youtube.com/watch?v=NTc5FXmnWYc)
3. [Email Verification using Laravel Fortify](https://www.youtube.com/watch?v=X0ebWjcQ-uc)
4. [Two Factor Authentication (2FA) with Laravel Fortify](https://www.youtube.com/watch?v=rDCqS277dVQ)


## How To Use This?

Download or clone this repo
```shell
$ git clone https://github.com/qirolab/laravel-fortify-example.git
```

Install all dependency required by Laravel.
```shell
$ composer install
```

Generate app key, configure `.env` file and do migration.
```shell
# create copy of .env
$ cp .env.example .env

# create Laravel key
$ php artisan key:generate

# run migration
$ php artisan migrate
```

Register at mailtrap.io or other service and paste credentials at .env to send messages:
```dotenv
MAIL_MAILER=smtp
MAIL_HOST=sandbox.smtp.mailtrap.io
MAIL_PORT=2525
MAIL_USERNAME=123456789
MAIL_PASSWORD=987654321
MAIL_ENCRYPTION=null
MAIL_FROM_ADDRESS=admin@localhost
MAIL_FROM_NAME="${APP_NAME}"
```
