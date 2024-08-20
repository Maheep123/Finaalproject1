Project 1: Library Management System
Project Structure:
•	AddBook.java: Handles the logic for adding new books to the library.
•	Admin.java: Manages administrative functionalities like adding or deleting books.
•	Book.java: Represents the book entity with attributes like title, author, etc.
•	BorrowBook.java: Manages the process of borrowing a book from the library.
•	Borrowing.java: Tracks borrowing records and handles related operations.
•	CalculateFine.java: Computes fines for overdue borrowed books.
•	Database.java: Interfaces with the database to store and retrieve data for the library.
•	DeleteAllData.java: Provides functionality to delete all data from the system.
•	DeleteBook.java: Handles deletion of specific books from the library.
•	Exit.java: Manages the process of safely exiting the application.
•	IOOperation.java: Handles input/output operations, possibly for file handling.
•	Main.java: The main entry point of the application, initializing and starting the system.
•	NormalUser.java: Manages functionalities available to normal users like borrowing books.
•	Order.java: Represents an order placed by a user for a book.
•	PlaceOrder.java: Manages the process of placing an order for a book.
•	ReturnBook.java: Handles the process of returning borrowed books.
•	Search.java: Provides search functionality to find books in the library.
•	User.java: Represents a user entity with attributes like username, password, etc.
•	ViewBooks.java: Displays the list of available books in the library.
•	ViewOrders.java: Displays the list of orders placed by users.

Overview
This is a simple Library Management System written in Java. The system allows administrators to manage books, users to borrow and return books, and tracks borrowing records along with fines for overdue returns. It provides functionalities for both administrative and normal user roles.

Features
Admin Functions:

Add new books
Delete books
View all books
Delete all data (use with caution)
User Functions:

Search for books
Borrow and return books
View borrowed books
Calculate fines for overdue returns

Usage
Run the Main.java file to start the application.
Follow the on-screen instructions to perform various actions like adding books, borrowing books, etc.
Database Configuration
The Database.java class handles all the database operations.
Ensure the database is properly configured and connected.
The structure should include tables for storing books, users, orders, and borrowing records.
