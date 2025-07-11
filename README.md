# Filament Google OAuth Login (via Ngrok)

Proyek ini merupakan integrasi **Google Login OAuth 2.0** dengan Laravel dan Filament Admin Panel. Cocok digunakan saat development/testing menggunakan **Ngrok**.

---

## 🔧 Requirements

- Laravel 10 atau 11
- FilamentPHP v3
- Composer
- Ngrok (akun gratis cukup)
- Google Cloud Console (OAuth Client ID)

---

## ⚙️ Instalasi

### 1. Clone proyek dan install dependency

```bash
git clone https://github.com/username/filament-google-login.git
cd filament-google-login
composer install
cp .env.example .env
php artisan key:generate
