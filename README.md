# TALL stack starter with Filament

- **T**ailwind css v3
- **A**lpinejs v3
- **L**aravel v11
- **L**ivewire v3
- Filament v3

This is a basic starter template for tall stack project with filament as admin panel. 


## Quick setup

#### Copy env file

```bash
cp .env.example .env
```

#### Create sqlite database file (Or connect to your choice of database)
```bash
touch database/database.sqlite
```

#### Install php packages

```bash
composer install
```

#### Install nodejs packages

```bash
pnpm i
```

#### Generate app key

```bash
php artisan key:generate
```

#### Migrate database

```bash
php artisan migrate
```

#### Make filament user

```bash
php artisan make:filament-user
# follow prompts instructions
```

#### Run build command to generate assets

```bash
pnpm build
```

## Run locally

#### Start laravel development server

```bash
php artisan serve
```

#### Start vite development server (Optional sometime)

```bash
pnpm dev
```

<cite>- mfazail ;)</cite>