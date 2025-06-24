```markdown
# 📚 Laravel Library Management System

![PHP Version](https://img.shields.io/badge/PHP-8.0%2B-blue)
![Laravel Version](https://img.shields.io/badge/Laravel-9.x-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A complete web-based library management system built with Laravel framework, featuring book cataloging, member management, and loan tracking.

## ✨ Features

- **Book Management** (CRUD operations)
- **Member Registration & Management**
- **Loan/Return System** with due date tracking
- **Admin Dashboard** with analytics
- **Search Functionality** for books/members
- **User Authentication** (Librarian/Member roles)
- **Reports Generation** (PDF/Excel exports)

## 🛠️ Technology Stack

- **Backend**: Laravel 9
- **Frontend**: Blade Templates, Bootstrap 5
- **Database**: MySQL
- **Authentication**: Laravel Breeze/Jetstream
- **Additional Packages**: 
  - Laravel Excel (Export/Import)
  - Spatie Permissions (Role management)

## 🚀 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mengucop/LaravelLibraryManagementSystem.git
   cd LaravelLibraryManagementSystem
   ```

2. **Install dependencies**:
   ```bash
   composer install
   npm install
   ```

3. **Setup environment**:
   ```bash
   cp .env.example .env
   php artisan key:generate
   ```

4. **Configure database**:
   - Create MySQL database
   - Update `.env` file:
     ```ini
     DB_DATABASE=your_db_name
     DB_USERNAME=your_db_user
     DB_PASSWORD=your_db_password
     ```

5. **Run migrations & seed data**:
   ```bash
   php artisan migrate --seed
   ```

6. **Start development server**:
   ```bash
   php artisan serve
   npm run dev
   ```

## 👥 Default Accounts

**Admin Account**:
- Email: admin@library.com
- Password: password

**Librarian Account**:
- Email: librarian@library.com
- Password: password

## 📜 License

This project is open-source under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

For questions or support, contact me
```
