# BUMASYS
## Features
- [x] Multi-Tenant
- [x] Modular
   - [ ] CRM
      - [ ] Omnichannel
         - [ ] WhatsApp
         - [ ] Telegram
   - [ ] Inventory Management
   - [ ] Sales and Distribution
   - [ ] Asset Management
   - [ ] Purchasing Management
   - [ ] Import and Export Management
   - [ ] Publishing Management
- [x] Dynamic Role and Permission 
- [x] Live Chat

## Getting Started

### Prerequisites

- Web Server => Nginx / Apache
- [PHP](https://php.net/) => ^8.0
- [PostgreSQL](https://www.postgresql.org/) => ^13.0
- [Composer](https://getcomposer.org/download/) => ^2.3.7
- [Redis](https://redis.io/download/) => ^7.0
- [NodeJS](https://nodejs.org/en/) => ^16.0
> For testing can use [Laragon](https://laragon.org/)
### Developing

1. Copy `.env.example` to `.env`
2. Setting all `MAIL_` in `.env`
3. Run `composer install` to install server dependencies.
4. Run `php artisan key:generate` to generate key.
5. Run `php artisan migrate --seed` and `php artisan module:seed` to generate table and dummy data.
6. Run `php artisan serve` to start the development server.
7. Open `127.0.0.1:8000` in browser.
