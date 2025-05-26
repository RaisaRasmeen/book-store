![image alt](https://github.com/RaisaRasmeen/book-store/blob/83f0cfc2eb0c08ef39fa80e13a8ca2f36e7299bc/bookstore-copy/IMG-20250526-WA0003.jpg)
Book Store Management System

A web-based application built with Laravel and MySQL to manage books efficiently with CRUD functionalities, pagination, and user-friendly UI.

Features

Dashboard: View all books in a paginated table.

Add Book: Form to add new book records.

View Details: Detailed view of individual books.

Update Book: Edit existing book information.

Delete Book: Delete book records with confirmation.

Database: MySQL with structured books table.


Tools & Technologies

PHP: v8.3 or above

Laravel: v11 or above

MySQL: Latest version

Development Environment: Laragon (recommended)

Frontend: Bootstrap or Tailwind (optional enhancements)


Database Schema

CREATE TABLE books (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255),
    author VARCHAR(255),
    isbn VARCHAR(100),
    price DECIMAL(10,2),    
    stock INT
);

Installation

1. Clone the repository:

git clone https://github.com/yourusername/book-store-management.git


2. Navigate to the project directory:

cd book-store-management


3. Install dependencies:

composer install
npm install && npm run dev


4. Create .env file:

cp .env.example .env
php artisan key:generate


5. Configure your .env file with database credentials.


6. Run migrations:

php artisan migrate


7. Launch the application:

php artisan serve



Optional Enhancements

Search by title/author

Form validation & error handling

Flash messages for user feedback


Screenshots

Dashboard with pagination

Add Book form

Detailed Book View

Update & Delete buttons


License

This project is part of the Web Engineering Lab Final Project and is for educational purposes only.
