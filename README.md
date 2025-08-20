# Laravel Inertia Vue Learning Path 🚀

This repository is my **learning project** where I started building a modern Laravel application **from scratch** using:

- [Laravel](https://laravel.com/docs) – Backend framework  
- [Inertia.js](https://inertiajs.com/) – Connects Laravel with Vue without building a full API  
- [Vue.js](https://vuejs.org/) – Frontend framework  
- [Vite](https://vitejs.dev/) – Fast build tool for frontend assets  
- [Tailwind CSS](https://tailwindcss.com/docs) – Utility-first CSS framework  

I did **not** use any starter kits (like Laravel Breeze or Jetstream).  
Instead, I followed each documentation step by step to understand the **core setup** manually.

---

## 🎯 Goal
- Learn how Laravel + Inertia + Vue integrate together.
- Understand how Vite handles asset bundling.
- Practice styling with Tailwind CSS.
- Build a foundation for future Laravel + Vue projects.

---

## ⚡ Features (so far)
- Laravel backend with Vue frontend via Inertia.
- TailwindCSS integration for styling.
- Vite-powered development and build process.
- Basic page routing with Inertia.

---

## 🛠️ Installation & Setup
Clone the repo and install dependencies:

```bash
git clone https://github.com/your-username/laravel-inertia-vue.git
cd laravel-inertia-vue

# Backend dependencies
composer install

# Frontend dependencies
npm install
```
Set up your .env file and run migrations:
```bash
cp .env.example .env
php artisan key:generate
php artisan migrate
```
Run the development servers:
```bash
php artisan serve
npm run dev
```

**📝 Notes**

This repo is not a production-ready app — it’s a learning path.
I’m documenting every step so I understand why each piece is needed instead of relying on pre-built starter kits.
