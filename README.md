Project (12) - 🏦 Bank Management System – C++ (OOP)
🏦 Bank Management System – C++ (OOP)
📌 Project Overview

This project is a full-featured console-based Bank Management System developed using C++, with a strong focus on Object-Oriented Programming (OOP) principles.

The system simulates a real-world banking environment, including client management, user management with permissions, authentication, and financial transactions, all organized through a clean, menu-driven console interface.

🚀 Key Features
🔐 Authentication & Security

Secure Login / Logout system

Role-based permissions for users

Access control for system functionalities

👥 Client Management

Add new clients

Update client information

Delete clients

Find specific clients

List all clients

👤 User Management

Add new users

Update user data

Delete users

Find users

List all users

Permission-based access control

💰 Transactions

Deposit money

Withdraw money

Calculate total balances

🧭 User Interface

Clean menu-driven console UI

Main Menu

Transactions Menu

Manage Users Menu

Clear navigation between screens

🛠️ Technologies & Concepts Used

C++

Object-Oriented Programming (OOP)

Encapsulation

Inheritance

Abstraction

Enums for menu handling

Modular system design

Clean Code principles

File-based data storage

Input validation

Separation of concerns

🧱 System Architecture

The system follows a screen-based layered architecture, where each screen is implemented as a separate class responsible for its own logic and display.

Examples:

clsMainScreen

clsManageUsersScreen

clsTransactionsScreen

clsClientListScreen

clsAddNewClientScreen

clsUser

This design ensures:

High readability

Easy maintenance

Scalability for future features

📂 Project Architecture
📂 Bank-System
│
├── 📁 Core
│   ├── clsPerson.h
│   ├── clsUser.h
│   ├── clsBankClient.h
│   ├── clsScreen.h
│   └── clsMainScreen.h
│
├── 📁 BusinessLogic
│   ├── clsTransaction.h
│   ├── clsDeposit.h
│   ├── clsWithdraw.h
│   ├── clsPermissions.h
│   └── clsLoginManager.h
│
├── 📁 Data
│   ├── clsFileHandler.h
│   ├── clsClientRepository.h
│   ├── clsUserRepository.h
│   └── DataFiles/
│       ├── Clients.txt
│       └── Users.txt
│
├── 📁 UI
│   ├── ClientScreens
│   │   ├── clsClientListScreen.h
│   │   ├── clsAddNewClientScreen.h
│   │   ├── clsDeleteClientScreen.h
│   │   ├── clsUpdateClientScreen.h
│   │   └── clsFindClientScreen.h
│   │
│   ├── UserScreens
│   │   ├── clsManageUsersScreen.h
│   │   ├── clsListUsersScreen.h
│   │   ├── clsAddNewUserScreen.h
│   │   ├── clsDeleteUserScreen.h
│   │   ├── clsUpdateUserScreen.h
│   │   └── clsFindUserScreen.h
│   │
│   ├── TransactionScreens
│   │   ├── clsTransactionsScreen.h
│   │   ├── clsDepositScreen.h
│   │   ├── clsWithdrawScreen.h
│   │   └── clsTotalBalancesScreen.h
│   │
│   └── clsLoginScreen.h
│
├── 📁 Utilities
│   ├── clsInputValidate.h
│   ├── clsDateTime.h
│   └── Global.h
│
└── main.cpp

🎯 Learning Outcomes

This project significantly improved my ability to:

Design complete systems, not just small programs

Apply OOP concepts in real-world scenarios

Build scalable and maintainable software

Think in terms of system flow and user experience

Write clean, structured, and reusable code

🔮 Future Improvements

Replace file storage with a database (SQL Server / SQLite)

Add transaction history with timestamps

Improve error handling using exceptions

Enhance security mechanisms

Convert the project into a GUI or web-based system

📌 Author

Ahmed Magdy Farouk
Software Developer | C++ | OOP | System Design

⭐ Feedback

Feedback and suggestions are always welcome.
Feel free to explore the project and share your thoughts 🚀
