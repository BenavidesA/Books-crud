# Library Management System

This is a C program to manage a small library. It allows you to register books, display registered books, search for a book by its ID or title, change the status of a book (from "Available" to "Checked out" or vice versa), and delete a book from the list.

## Features

### 1. **Register Book**
   Allows entering the data of a book, including its ID, title, author, publication year, and status (initially set as "Available"). It validates input to ensure that no more than 20 books are entered and that IDs are not duplicated.

### 2. **Display Books**
   Displays all registered books, including their ID, title, author, year, and status. Only books that have been successfully registered are shown.

### 3. **Search Book by ID**
   Allows searching for a book by its ID and displays the details of the found book, including its title, author, publication year, and status.

### 4. **Search Book by Title**
   Allows searching for a book by its title and displays the details of the found book.

### 5. **Change Book Status**
   Changes the status of a book between "Available" and "Checked out." This is useful for keeping track of books that have been borrowed.

### 6. **Delete a Book**
   Allows deleting a book from the list of registered books. The book is removed by searching for its title and shifting the remaining elements to fill the empty space.

### 7. **Exit**
   Ends the program execution.

## Data Structure

The program uses a structure called `Book` with the following fields:

- **ID**: A unique identifier for each book (integer).
- **Title**: The title of the book (string).
- **Author**: The author of the book (string).
- **Year**: The year of publication of the book (integer).
- **Status**: The status of the book, which can be "Available" or "Checked out" (string).

## Requirements

This program is written in C and uses the following standard libraries:

- `stdio.h`
- `string.h`

## Limitations
The program is limited to a maximum of 20 books.
Only unique IDs are allowed for each book, and the program validates the input to prevent duplicates.

