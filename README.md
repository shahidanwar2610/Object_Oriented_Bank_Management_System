# Object Oriented Bank Management System

A C++ command-line (CLI) application that simulates a full Bank Management System (BMS), comprising two sub-applications: **Bank Application** and **ATM Application**.  
Built using Object-Oriented Programming and a 3-Tier architecture; demonstrates account management, transactions, user login, and core banking functionalities.

---

## 🚀 Features

- Manage bank accounts: create, modify, delete accounts  
- Process deposits, withdrawals, transfers  
- ATM-like interactions: PIN/login, balance inquiry  
- CLI menus and user prompts for input validation  
- Separation of concerns via presentation, business, & data layers  

---

## 📋 Requirements

- Windows OS  
- g++ C++ compiler  
- Bash / Bash-like terminal (e.g. Git Bash, WSL)  

---

## ▶ How to Run

1. Clone this repository:  
   git clone https://github.com/shahidanwar2610/Object_Oriented_Bank_Management_System.git
   cd Object_Oriented_Bank_Management_System
Navigate to build folder:

2.bash
Copy code
cd build
Run the build script:

bash
Copy code
./run.sh
This will compile the code and produce main.exe.

If run.sh doesn’t work or you want to compile manually:

bash
Copy code
cd ../
g++ -I include -I include/libs -I include/libs/Data_Manip src/*.cpp -o main.exe
./main.exe
🔐 Demo Credentials
Username: admin

Password: 1234
