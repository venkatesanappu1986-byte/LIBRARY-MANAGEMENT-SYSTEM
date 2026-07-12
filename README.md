# LIBRARY-MANAGEMENT-SYSTEM

# Library Management System

## Overview

The **Library Management System** is a simple console-based application developed to manage library operations efficiently. It helps in maintaining book records, managing book transactions, and storing library data using file handling. The system reduces manual work and provides an organized way to add, update, remove, search, issue, and return books.

## Features

### 1. Add New Book
- Automatically generates a unique **Book ID** for every new book.
- Allows the librarian to enter the **Book Name**, **Author Name**, and **Quantity**.
- Stores the newly added book information in the library records.

### 2. Update Book Details
- Update a book record using the **Book ID** and **book name**.
- Save the updated book information to the library records.

### 3. Remove Book
- Remove a book using the **Book ID** and **book name**.
- Permanently delete the selected book record from the library.

### 4. Search Book
- Search for a book using the **Book ID**,**book name** and **author name**.
- Display the complete details of the book if the record exists.
- Show an appropriate message if the book is not found.

### 5. View All Books
- Display all available books in the library.
- Show details such as:
  - Book ID
  - Book Name
  - Author Name
  - Quantity

### 6. Issue Books to User
- Issue a book to a user using the **Book ID**.
- Store user and book issue details.
- Update the available quantity after issuing a book.

### 7. Return Book
- Return an issued book using the **Book ID**.
- to get **user id** ,**user name** and update issued book detail.
- Update the book availability after the return.
- Maintain accurate issue and return records.

### 8. View Issued Books
- Display all currently issued books.
- Show details of issued books and associated user information.

### 9. Save Data to Files
- Store all book records and issued book details in files.
- Ensure that data remains available even after closing the application.
- Load saved data whenever the program starts.
