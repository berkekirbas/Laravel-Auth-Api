# laravel-auth-api
A simple Auth Api written in php using [Laravel](https://laravel.com).

# Getting Started
Clone the project by running the command below:

`git clone https://github.com/berkekirbas/laravel-auth-api.git`

then run:

`composer install`

rename `.env.example` to `.env`
then run:

`php artisan key:generate`
`php artisan passport:install`

then fill your database details in your .env file

now you can run migrations:

`php artisan migrate`

then fill your Mail Server details in your .env file (if you if you don't want to use it remove sendApiTokens function from registerController)

then start the application:

`php artisan serve`

and visit http://localhost:8000 to see the application.

- [ ] Password Reset will fix it

# Postman Screenshots(Coming Soon)
