### CMS

    laravel -v
    laravel new laravel-cms
    cd laravel-cms\
    composer require laravel/jetstream
    php artisan jetstream:install livewire --teams
    npm install && npm run dev

CREO IL DB E LO SCRIVO IN .env

    php artisan migrate
    php artisan vendor:publish --tag=jetstream-views
    php artisan make:model Page -m
    php artisan make:livewire Pages
    php artisan make:livewire Frontpage

VAI SU https://github.com/amaelftah/laravel-trix PER INFO

    composer require te7a-houdini/laravel-trix
    php artisan vendor:publish --provider="Te7aHoudini\LaravelTrix\LaravelTrixServiceProvider"
    php artisan migrate

INSERISCI @trixassets DENTRO IL <HEAD> DEL TEMPLATE

```npm run dev ``` OGNI VOLTA CHE MODIFICO IL CSS O IL JS NELLA MIA APP
```php artisan jetstream:install inertia --teams``` OPZIONALE, SOLO PER PROVARE INERTIA

```composer require inertiajs/inertia-laravel```
 

