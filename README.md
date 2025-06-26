# Library Management System (Java OOP Project)

## 📘 Objective
A simple console-based Java application to manage a library. The system allows users to:
- View available books
- Issue a book
- Return a book

## 🛠️ Technologies Used
- Java (OOP Concepts)
- VS Code (or any Java IDE)
- Terminal/Command Prompt

## 📁 Project Structure
```
LibraryManagementSystem/
├── Book.java       // Book class (id, title, author, isIssued)
├── User.java       // User class (userId, name)
├── Library.java    // Handles book operations (add, issue, return)
├── Main.java       // Menu and execution logic
└── README.md       // Project guide
```

## 🚀 How to Run
1. Open terminal in the project folder.
2. Compile all Java files:
   ```bash
   javac *.java
   ```
3. Run the application:
   ```bash
   java Main
   ```

## 🔄 Features
- Add sample books to library
- Show list of all books
- Issue a book by ID
- Return a book by ID

## 💡 Concepts Applied
- Classes and Objects
- Encapsulation
- ArrayList usage
- Loops and conditionals
- User input handling with Scanner

## 📌 Note
This is a basic version of a library system. It can be extended to support:
- Storing multiple users
- Track who issued which book
- File-based or database persistence

---
**Created for learning OOP with Java.**