# telephone-directory-cpp
A console-based telephone directory application in C++ with account login, search, modify, and admin features.
📞 Telephone Directory — C++ Project

This project is a console-based telephone directory system implemented in C++.
It supports:

User Sign-Up / Login

Admin Access with special privileges

Add new contacts

Search contacts

Delete contacts

Modify existing entries

File-based storage using .dir files

# 🚀 Features
🔐 Authentication System

Sign-Up creates new account stored in Accounts.dir

Sign-In verifies username + hidden password

Special admin usernames: Admin or admin

Admin passwords: Root or root

# 📚 Directory Features

Add contact: First name, Last name, Phone number

Search contact

Delete contact

Modify existing contact

Stores all data in Directory.dir via file I/O

# 💾 File Handling

Uses:

Accounts.dir for account storage

Directory.dir for telephone entries

Temporary .dir files for modify/delete operations

🛠 Technologies Used

C++

File handling (fstream)

Console UI

Windows-specific libraries:

<conio.h>

<windows.h>

# 📂 How to Run

Install any C++ compiler (CodeBlocks, Dev C++, MinGW, VSCode with C++ extension).

Create a project and add telephone-directory.cpp to it.

Build & run.

# 📘 Learning Outcomes

File handling in C++

String processing

Basic authentication logic

Console UI development

CRUD operations using file streams
