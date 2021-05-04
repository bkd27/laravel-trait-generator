# Laravel Trait Generator
Laravel Generator For Creating New Traits

## Installation

Install using https://getcomposer.org/doc/05-repositories.md#vcs

Service auto-discovered if laravel ^5.5 else Add the service provider, open `config/app.php`, and add a new item to the providers array.

```
Bkd27\TraitGenerator\ServiceProvider::class,
```

That's it! You're all set to go. Run the `php artisan` command from the Terminal to see the new `make:trait` command.

## Usage

```
php artisan make:trait MyTrait
```
