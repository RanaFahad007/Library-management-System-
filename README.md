# Library-management-System-
# Library Management System (C++)

## 📚 Description

This is a console-based Library Management System developed in C++. It allows users to manage book records in a library, including operations such as adding books, searching by author/title/ID, displaying all books, and checking total book count.

## 🚀 Features

- Add book details (Title, Author, ID, Price, Issuance status)
- Display all stored book information
- Search books by:
  - Author name
  - Title
  - ID number
- View the total number of books available
- Simple user interface via console
- Exit functionality

## 🛠️ Technologies Used

- **C++**
- **Console I/O**
- `conio.h` for input pause (`_getch()`)

## 🧾 Functions Overview

| Function       | Description                                                |
|----------------|------------------------------------------------------------|
| `addbook()`    | Adds a new book to the system                              |
| `bookinfo()`   | Displays information of all books                          |
| `authorname()` | Lists all books by a specific author                       |
| `title()`      | Displays information of a specific book by title           |
| `idnumber()`   | Displays information of a specific book by ID number       |
| `total()`      | Shows total number of books added                          |
| `display()`    | Displays the welcome screen                                |

## 💡 How to Use

1. Compile the program using a C++ compiler (e.g., g++, Dev C++, Turbo C++).
2. Run the program.
3. Choose from the available options:
   - `1` → Add Book
   - `2` → Display All Books
   - `3` → Search by Author
   - `4` → Count Total Books
   - `5` → Search by Title
   - `6` → Search by ID
   - `7` → Exit

## 📌 Limitations

- No data persistence (data lost on exit)
- Maximum of 50 books (due to fixed array size)
- Input handling could be improved (e.g., accepting multi-word strings)

## 📈 Future Improvements

- Use of file handling for data storage
- Dynamic memory allocation (replace static array)
- Better UI/UX
- Use of classes for improved design (OOP)

## 📑 Author

Created as a basic C++ project for learning purposes.

