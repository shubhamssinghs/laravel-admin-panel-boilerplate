
# Laravel Admin Panel Boilerplate

This contains tailwind css admin panel with Laravel Breeze auth.

## How to Setup

### Step 1 : Install Packages

```
composer install
```


### Step 2 : Copy the .env.expample to .env

```
cp .env.expample .env
```

### Step 3 : Setup Database details in .env file

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=admin_panel
DB_USERNAME=root
DB_PASSWORD=
```

### Step 4 : Run npm

```
npm install & npm run dev
```

### Step 5 : Migrate Database

```
php artisan migrate
```

### Step 6 : Run Development Serve

```
php artisan serve
```
