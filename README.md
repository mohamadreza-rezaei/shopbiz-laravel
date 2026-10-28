# shopbiz-laravel

Modular Laravel shop with an admin panel (Blade + Bootstrap 4 / Tailwind assets).

## Stack

- Laravel
- Modular structure under `Modules/`
- Blade templates
- Intervention Image, Sanctum, Socialite, DomPDF, SEO tools

## Setup

```bash
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
```

Optional frontend assets:

```bash
npm install
npm run dev
```

## Admin

With Laravel Herd (or similar), the panel was used at:

`https://shopbiz.test/panel`
