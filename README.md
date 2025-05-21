# E-Booking Portal: A User-Friendly Booking Management System

## Project Overview
The **E-Booking Portal** is a Python-based library management system with a MySQL database backend. This project uses a GUI developed with Python's Tkinter library. It's designed to simplify the management of library bookings and provide a user-friendly experience for both students and admins.

### Technologies Used:
- **Python**: 3.11.2
- **GUI Framework**: Tkinter
- **Database**: MySQL
- **Backend**: MySQL Connector for Python

---

## Features
- **Single Page Interface**: Consolidated functionality on one page for simplicity.
- **Dynamic Widgets**: Widgets (buttons, entry boxes) are activated based on user actions.
- **Library Management**: View all books, add, delete, borrow, and return books.
- **Search Functionality**: Allows users to search for books by title or author.
- **Confirmation Prompts**: For critical actions like book deletion.
- **Automatic Restart**: The system refreshes after performing key actions.

---

## Installation

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/krishnasree76/E-library-books-booking.git
    ```

2. **Install Python Dependencies**:
    ```bash
    pip install mysql-connector-python
    ```

3. **Database Setup**:
    - Create a database and table:
    ```sql
    CREATE DATABASE library_db;
    USE library_db;
    CREATE TABLE books (
        id INT AUTO_INCREMENT PRIMARY KEY,
        title VARCHAR(255) NOT NULL,
        author VARCHAR(255) NOT NULL
    );
    ```

4. **Run the Application**:
    ```bash
    python library.py
    ```


## How It Works

1. **Login**: Admin and student log into their respective dashboards.
2. **Student Dashboard**:
    - **Make Request**: Students can request books or leave.
    - **View Request**: Students can check the status of their requests.
3. **Admin Dashboard**:
    - **Student Requests**: Admin can accept or decline student requests.
    - **Manage Books**: Admin can view and manage books in the library.

---

## Conclusion
The **E-Booking Portal** provides a simple and effective solution for library management, prioritizing user experience and ease of use. With an intuitive GUI and streamlined functionality, it serves as an excellent tool for managing library bookings.

---

