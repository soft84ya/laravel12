# Laravel Project Setup

This guide will help you set up the Laravel project on your local system after cloning from GitHub.

---

## 🚀 Steps to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/soft84ya/laravel12.git
composer install
copy .env.example .env     # For Windows
# OR
cp .env.example .env       # For Linux / Mac

php artisan key:generate

php artisan migrate

php artisan serve



