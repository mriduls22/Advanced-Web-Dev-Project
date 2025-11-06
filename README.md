# Laravel Blog with Admin Panel (Mini Project)

This project is a simple **Blog Website** built using **PHP and the Laravel Framework**.  
It includes a **CRUD-enabled Admin Panel**, allowing the administrator to manage blog posts efficiently.

---

## ✨ Features

### 📝 User Side
- View all blog posts
- Read full blog articles
- Responsive user-friendly UI

### 🔐 Admin Panel
- Secure Login System
- Add New Blog Posts (Create)
- Edit Existing Posts (Update)
- Delete Unwanted Posts (Delete)
- View All Posts (Read)
- Dashboard Overview

---

## 🛠 Tech Stack
| Component | Technology |
|----------|------------|
| Language | PHP |
| Framework | Laravel |
| Frontend | Blade Templates / HTML / CSS |
| Database | MySQL |
| Authentication | Laravel Auth / Middleware |

---

## ⚙️ Installation Guide

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/laravel-blog-admin.git
   cd laravel-blog-admin

2. **Install Dependencies**
   ```bash
   composer install

3. **Setup Environment File**
   ```bash
   cp .env.database .env
  Have to update Credentials inside .env

4. **Generate Application Key**
   ```bash
   php artisan key:generate

5. **Run Database Migrations**
   ```bash
   php artisan migrate
6. **Start the Development Server**
   ```bash
   php artisan serve


