# File-Based Notes Saver

## Project Overview

The **File-Based Notes Saver** is a simple C++ application that allows users to create, save, view, and clear personal notes using file handling.

The project demonstrates the practical use of C++ file handling concepts, especially the `fstream` library. Notes are stored permanently in a text file so that they can be accessed whenever the program is executed.

## Objective

The main objective of this project is to understand and implement file handling in C++.

The project demonstrates:

* Writing data to files
* Reading data from files
* Appending new notes
* Clearing stored notes
* Using `ifstream` and `ofstream`
* Using the `fstream` concept for file-based data storage

## Features

* Add new notes
* View saved notes
* Store notes permanently in a text file
* Append multiple notes without deleting previous notes
* Clear all saved notes
* Simple menu-driven interface
* Easy to use and understand

## Technologies Used

* **Programming Language:** C++
* **File Handling:** `fstream`
* **Storage:** Text file (`notes.txt`)
* **Development Environment:** Any C++ compiler such as Code::Blocks, Dev-C++, Visual Studio Code, or online C++ compiler

## Project Structure

```text
file-based-notes-saver-1-/
│
├── main.cpp
├── notes.txt
├── README.md
├── documentation/
│   └── Project-Documentation.pdf
│
└── screenshots/
    ├── menu.png
    ├── add-note.png
    └── view-notes.png
```

## File Handling Flow

```text
Start
  |
  v
Display Menu
  |
  +---- Add Note
  |       |
  |       v
  |   Open notes.txt
  |       |
  |       v
  |   Enter Note
  |       |
  |       v
  |   Append Note
  |       |
  |       v
  |   Close File
  |
  +---- View Notes
  |       |
  |       v
  |   Open notes.txt
  |       |
  |       v
  |   Read Notes
  |       |
  |       v
  |   Display Notes
  |       |
  |       v
  |   Close File
  |
  +---- Clear Notes
  |       |
  |       v
  |   Open File
  |   in Truncate Mode
  |       |
  |       v
  |   Delete Contents
  |
  +---- Exit
          |
          v
         End
```

## How to Run

### Step 1

Download or clone this repository.

### Step 2

Open `main.cpp` in a C++ development environment.

### Step 3

Compile the program.

```bash
g++ main.cpp -o notes
```

### Step 4

Run the program.

```bash
./notes
```

On Windows, you can run:

```bash
notes.exe
```

## Sample Output

```text
============================
    FILE-BASED NOTES SAVER
============================
1. Add Note
2. View Notes
3. Clear Notes
4. Exit
Enter your choice: 1

Enter your note: Complete C++ assignment
Note saved successfully!
```

### Viewing Notes

```text
============================
    FILE-BASED NOTES SAVER
============================
1. Add Note
2. View Notes
3. Clear Notes
4. Exit
Enter your choice: 2

----- Your Notes -----
- Complete C++ assignment
- Study file handling
- Prepare project presentation
```

## Advantages

* Simple and easy to use
* No database is required
* Notes are stored permanently
* Demonstrates basic C++ file handling
* Suitable for beginners learning C++

## Future Enhancements

The project can be improved by adding:

* Edit or update notes
* Delete individual notes
* Search notes
* Date and time for each note
* Password protection
* Graphical User Interface
* Database integration
* User login system

## Conclusion

The File-Based Notes Saver successfully demonstrates how C++ file handling can be used to create a simple data-storage application. The project provides practical experience with reading, writing, and appending data using files.

It also helps in understanding how information can be stored permanently without using a database.

## Team

**Project:** File-Based Notes Saver

**Repository:** `file-based-notes-saver-1-`

**Team Members:**

* Member 1
* Member 2
* Member 3
* Member 4

## License

This project is created for educational and academic purposes.
