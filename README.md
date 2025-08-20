# 📚 Laravel Book Store

A modern **Book Store Application** built with **Laravel 10**.  
Supports local book management, categories, and integrates with the **Google Books API**.

---

## 🚀 Quick Start (One Copy Section)

Follow these steps to run the project on your local machine:

```bash
# 1️⃣ Clone repository
git clone https://github.com/your-username/book-store.git
cd book-store

# 2️⃣ Install dependencies
composer install
npm install && npm run dev

# 3️⃣ Setup environment
cp .env.example .env
php artisan key:generate

# 4️⃣ Configure database in .env
# Example:
# DB_CONNECTION=mysql
# DB_HOST=127.0.0.1
# DB_PORT=3306
# DB_DATABASE=bookstore
# DB_USERNAME=root
# DB_PASSWORD=

# 5️⃣ Run migrations and seed demo data
php artisan migrate --seed

# 6️⃣ Storage link for book images
php artisan storage:link

# 7️⃣ Add Google Books API Key in .env
# GOOGLE_BOOKS_API_KEY=your_api_key_here

# 8️⃣ Update config/services.php
# 'google_books' => [
#     'api_key' => env('GOOGLE_BOOKS_API_KEY'),
# ],

# 9️⃣ Run development server
php artisan serve
