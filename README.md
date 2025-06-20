# OOP345V1A

Library Management System – Assignment 1
Course: C++ Advanced Programming
Student: Abishek Raveendranath
Overview
This C++ program simulates a basic library management system where you can keep track of books and magazines in a library. Users can add new items, display all items, search or sort by various attributes like title or author, and track which books are currently borrowed and by whom. Borrowing activities are recorded using a mapping of book ISBNs to borrow information.
Features
Book and Magazine Management:
Add, display, and sort books and magazines.
Borrowing System:
Track which books are currently borrowed and by whom, using a std::map for fast lookup and association.
Templates and STL:
Uses template classes and function templates for flexible catalog/search operations.
Polymorphism:
All items are managed through base class pointers, allowing uniform display and operations.
File Structure
- LibraryItem.h / LibraryItem.cpp – Abstract base class for library items
- Book.h / Book.cpp – Book class
- Magazine.h / Magazine.cpp – Magazine class
- Catalog.h – Templated catalog class (header only)
- Functors.h – Functors for sorting books
- Utility.h – Function templates for searching
- main.cpp – Demo with catalog usage and borrowing system
How to Compile and Run
1. Open the project in Visual Studio or any C++17-compatible environment.
2. Make sure all .h and .cpp files are in your project directory.
3. Build the project.
4. Run the program.
