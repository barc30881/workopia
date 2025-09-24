# 🚀 Workopia (Laravel 11)

![Workopia Screenshot](https://github.com/bradtraversy/workopia-laravel/blob/main/public/images/screen.png?raw=true)

Workopia is a modern **job listing platform** built with **Laravel 11**, featuring authentication, resume uploads, interactive UI, and an employer dashboard.  

🔗 **Live Demo:** [https://www.workopia.it/](https://www.workopia.it/)  

---

## ✨ Features

- 📝 Job Listing **CRUD** (Create, Read, Update, Delete)  
- 🔐 Authentication & **Authorization Policies**  
- 🖼️ Profile Avatar Upload  
- ⚡ Reusable **Blade UI Components**  
- 🎨 Vite + Tailwind CSS Integration  
- ⭐ Bookmarking System  
- 📄 Apply for Jobs & Upload Resume  
- 🧑‍💻 Personalized **User Dashboard**  
- ⚡ Interactive UI with **Alpine.js**  
- 🌱 Database Seeder for sample data  
- 🔍 Job Search & Filters  
- 🗺️ Mapbox Integration for job locations  
- 📧 Email Notifications (Mailtrap setup)  
- 📑 Pagination for job listings  

---

## 🛠️ Tech Stack

- **Backend:** Laravel 11 (PHP 8+)  
- **Frontend:** Blade, TailwindCSS, Alpine.js  
- **Build Tool:** Vite  
- **Database:** MySQL / MariaDB  
- **Maps:** Mapbox API  
- **Mail:** Mailtrap  

---

## 📂 Project Setup

```bash
# Clone repo
git clone https://github.com/barc30881/workopia.git

cd workopia

# Install dependencies
composer install
npm install && npm run dev

# Copy environment file
cp .env.example .env

# Generate app key
php artisan key:generate

# Run migrations and seed
php artisan migrate --seed

# Start server
php artisan serve
