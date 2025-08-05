# Book_shelf_management
A Python console-based bookstore inventory system. It uses SQLite for database management, enabling clerks to add, update, delete, search, and view books. The project emphasizes code modularity, error handling, and data validation for a robust solution.
# Bookstore Inventory Management System

## Project Description

This project is a Python-based application for a bookstore's inventory management. [cite_start]The program, named shelf_track, allows a clerk to manage book data in a SQLite database[cite: 26, 35]. [cite_start]It serves as a practical demonstration of Python and SQL skills, focusing on creating a functional and maintainable software solution[cite: 8].

[cite_start]The application interacts with a database named ebookstore, which contains two main tables: book and author[cite: 35, 52]. [cite_start]The author table is linked to the book table through a foreign key (authorID) to store and retrieve detailed information about each book's author[cite: 78].

## Features

The program offers a comprehensive menu-driven interface with the following functionalities:

* [cite_start]*Enter book*: Add new book records to the database[cite: 28].
* [cite_start]*Update book*: Modify existing book information, such as the quantity, title, or author ID[cite: 29, 45].
* [cite_start]*Delete book*: Remove a book record from the database[cite: 30].
* [cite_start]*Search books*: Query the database to find a specific book by its title or author[cite: 31].
* [cite_start]*View details of all books*: Display a user-friendly list of all books, including the title, author's name, and author's country[cite: 61].

## Technologies Used

* *Python*: The primary programming language for the application logic.
* *SQLite*: The relational database management system used to store the book and author data.
* [cite_start]*SQL*: Used for all database operations, including creating tables, inserting data, updating records, and performing searches[cite: 8, 79].

## Best Practices

[cite_start]The development of this project followed several best practices for code maintainability and security[cite: 82]:

* [cite_start]*Code Modularity*: The program is divided into smaller, reusable functions for each specific task (e.g., enter_book(), update_book(), delete_book()) to improve readability and maintainability[cite: 83, 84].
* [cite_start]*Error Handling*: Robust error handling is implemented to manage unexpected user inputs and database errors, ensuring the program provides user-friendly messages[cite: 85, 86].
* [cite_start]*Data Validation*: User inputs are validated to prevent data inconsistencies and security risks such as SQL injection attacks[cite: 87].
* [cite_start]*Context Managers*: The SQLite database connection is handled using with statements to ensure that the connection is automatically and safely closed after operations, preventing database locks[cite: 90].

## Getting Started

### Prerequisites

* Python 3.x installed on your system.

### Installation

1.  Clone this repository to your local machine:
    git clone https://github.com/your_username/your_repository_name.git
2.  Navigate to the project directory:
    cd bookstore_project
3.  Run the Python script:
    python your_script_name.py

*Note: The script will automatically create the book_shelf.db file and populate the necessary tables on the first run.*

## Future Enhancements
* Adding a graphical user interface (GUI).
* Implementing more advanced search functionalities.
* Adding a login system for different user roles (e.g., clerk, manager).
