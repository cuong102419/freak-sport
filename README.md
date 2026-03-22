# 🛍️ Freak Sport — E-commerce Website for Sneakers

A full-stack e-commerce platform for sneakers built with **Laravel**, featuring real-time notifications, online payment integration, and automated order management.

---

## 🚀 Tech Stack

| Layer | Technology |
|---|---|
| Backend | Laravel (MVC) |
| Frontend | Blade, Bootstrap, JavaScript |
| Database | MySQL |
| Real-time | Pusher (WebSocket) |
| Payment | VNPay, MoMo |
| Auth | Laravel Auth |
| Automation | Laravel Scheduler, Windows Task Scheduler |
| Tools | Git, Postman |

---

## ✨ Features

- 🔐 User authentication (register, login, logout)
- 🛒 Shopping cart & order management
- 💳 Online payment via **VNPay** and **MoMo**
- 🔔 Real-time order notifications with **Pusher (WebSocket)**
- ⚙️ Automated order completion using **Laravel Scheduler**
- 🗂️ Admin dashboard for managing products, orders, and users
- 🗄️ MySQL database with optimized schema for product catalog

---

## ⚙️ Installation

```bash
# 1. Clone the repository
git clone https://github.com/cuong102419/freak-sport.git
cd freak-sport

# 2. Install PHP dependencies
composer install

# 3. Install Node dependencies
npm install

# 4. Setup environment
cp .env.example .env
php artisan key:generate

# 5. Configure your .env file
# DB_DATABASE=freak_sport
# PUSHER_APP_ID=your_pusher_app_id
# PUSHER_APP_KEY=your_pusher_key
# PUSHER_APP_SECRET=your_pusher_secret
# VNPAY_TMN_CODE=your_vnpay_code
# VNPAY_HASH_SECRET=your_vnpay_secret

# 6. Run migrations & seed data
php artisan migrate --seed

# 7. Build assets
npm run dev

# 8. Start the server
php artisan serve
```

---

## 📁 Project Structure

```
freak-sport/
├── app/
│   ├── Http/Controllers/     # Business logic
│   ├── Models/               # Eloquent models
│   └── Console/Commands/     # Scheduled tasks
├── database/
│   ├── migrations/           # Database schema
│   └── seeders/              # Sample data
├── resources/
│   └── views/                # Blade templates
└── routes/
    └── web.php               # Application routes
```

---

## 👨‍💻 Author

**Pham Manh Cuong**
- Email: cuongmanh1024@gmail.com
- GitHub: [@cuong102419](https://github.com/cuong102419)
