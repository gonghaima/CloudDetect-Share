# Test Scenario: Library Management System
Overview:
You are tasked with developing a simple library management system console application using C# .NET Core. The system should allow librarians to manage books, patrons, and book loans.

## Requirements:

- Book Management:
Add new books to the library.
Remove books from the library.
Display a list of all books in the library.

- Patron Management:
Add new patrons to the library.
Remove patrons from the library.
Display a list of all patrons in the library.

- Book Loan Management:
Allow patrons to borrow books.
Allow patrons to return books.
Display a list of all books currently borrowed by a specific patron.
Display a list of all overdue books.
- Additional Features:
Implement validation to ensure that books cannot be borrowed if they are already on loan.
Implement a due date for borrowed books and mark them as overdue if not returned by the due date.
Implement error handling for invalid input.

## Guidelines:
Use Object-Oriented Programming (OOP) principles such as encapsulation, inheritance, and polymorphism where applicable.
Utilize appropriate data structures (e.g., lists, dictionaries) to store books, patrons, and loan information.
Implement a simple console interface for interacting with the library system.
Write unit tests to ensure the correctness of your code.
Separate concerns by organizing your code into classes and methods with clear responsibilities.

##Bonus Tasks (Optional):
Implement persistence using a simple file-based or in-memory database.
Enhance the console interface with a user-friendly menu system.
Implement logging to record important events or errors.
Add the ability to search for books by title, author, or genre.

## Example Usage:

```shell
Welcome to the Library Management System!

1. Add Book
2. Remove Book
3. Display All Books
4. Add Patron
5. Remove Patron
6. Display All Patrons
7. Borrow Book
8. Return Book
9. Display Patron's Borrowed Books
10. Display Overdue Books
0. Exit

Please enter your choice: 1

Enter book title: C# Programming Basics
Enter author: John Smith
Enter genre: Programming
Book added successfully!

...

```