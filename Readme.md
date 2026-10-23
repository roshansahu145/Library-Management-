# Library Management System

A lightweight, console-based Library Management System built in C. This application allows users to store, view, and search for books in a local catalog using a simple interactive menu.

## Features

* **Add Book**: Easily add a new book to the library by entering its Title, Author, and Year of publication.
* **Display Books**: View a complete list of all books currently stored in the system.
* **Search by Title**: Quickly find a specific book by typing its exact title.
* **Search by Author**: Retrieve a list of all books written by a specific author.
* **Capacity**: The system currently supports up to 100 books.

## Files

* `LibraryManagementSystem.c`: The main source code file containing the application logic.

## Prerequisites

To compile and run this application, you will need a C compiler installed on your system (such as GCC).

## How to Compile and Run

1. Open your terminal or command prompt.
2. Navigate to the directory where `LibraryManagementSystem.c` is located.
3. Compile the C program using a compiler like `gcc`:
   ```bash
   gcc LibraryManagementSystem.c -o LibraryManagementSystem
   ```
4. Run the compiled executable:
   * **On Linux/macOS:**
     ```bash
     ./LibraryManagementSystem
     ```
   * **On Windows:**
     ```bash
     LibraryManagementSystem.exe
     ```

## Usage

Upon running the application, you will be greeted with a menu:

```text
Library Management System
1. Add Book
2. Display Books
3. Search by Title
4. Search by Author
5. Exit
Enter your choice: 
```

Simply type the number corresponding to the action you wish to perform and press **Enter**. Follow the on-screen prompts to input book details or search queries.

## Technical Notes

* **In-Memory Storage:** This application uses in-memory data structures (arrays) to manage the books. All data is lost when the application is closed. 
* **Limits:** The maximum number of books is defined by `MAX_BOOKS`, which is currently set to 100.