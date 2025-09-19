# Koinao

**Koinao** is a modular web platform built with Laravel and Vue 3, designed for scalable, multi-role community applications.

## 🧱 Tech Stack & Versions

| Layer        | Technology                 | Version       |
|--------------|----------------------------|---------------|
| Backend      | Laravel Framework          | ^12.0         |
| Frontend     | Vue                        | ^3.5.13       |
| Rendering    | Inertia.js (Laravel + Vue) | ^2.0 / ^2.1.0 |
| Styling      | Tailwind CSS               | ^4.1.1        |
| UI Kit       | ShadCN for Vue             | (latest)      |
| Icons        | Lucide Vue Next            | ^0.468.0      |
| Auth System  | Laravel Fortify            | ^1.30         |
| Dev Server   | Vite                       | ^7.0.4        |
| Testing      | Pest PHP                   | ^4.1          |
| Formatter    | Prettier                   | ^3.4.2        |
| Linter       | ESLint                     | ^9.17.0       |
| Typescript   | TypeScript                 | ^5.2.2        |

## ⚙️ Common Commands

```bash
# Install dependencies
npm install
composer install

# Development mode
npm run dev
php artisan serve

# Run tests
php artisan test
```

## 📁 Key Directories

* resources/js/ – Vue 3 + TypeScript codebase
* routes/web.php – Inertia routes (server + client)
* tailwind.config.js – Custom styling rules
* tests/ – Pest-powered test suite

## 📄 License

MIT — Open for internal use, contributions welcome upon request.
