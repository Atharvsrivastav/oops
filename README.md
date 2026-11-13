# OOPS Practical Lab Work

Object-Oriented Programming (OOPS) practical laboratory assignments and mini project in C++.

## Student Details
- **Student Name:** Atharv Sharma
- **Subject:** Object-Oriented Programming (OOPS Lab)
- **Course:** B.Tech Computer Science and Engineering
- **University:** Ajeenkya DY Patil University (ADYPU), Pune

---

## Index of Experiments

| Exp No. | Experiment Title | Description |
| :---: | :--- | :--- |
| **01** | C++ Fundamentals | Basic data types, variables, constants, arithmetic/bitwise operators, and formatted output using `iomanip`. |
| **02** | Class Hierarchy & Access Specifiers | Real-world `BankAccount` and `SavingsAccount` classes demonstrating `private`, `protected`, and `public` access. |
| **03** | Constructors and Rule of 5 | Default, Parameterized, Copy (deep copy), Move constructor, and proper memory cleanup using Destructor. |
| **04** | Inheritance | Single and Multilevel inheritance using `Person` -> `Student` -> `GraduateStudent` with constructor chaining. |
| **05** | Runtime Polymorphism | Abstract base class `Shape` with pure virtual function `area()`, implemented by `Circle`, `Rectangle`, and `Triangle`. |
| **06** | Compile-Time Polymorphism | `Complex` number class demonstrating function overloading (`add`) and operator overloading (`+`, `-`, `*`, `<<`). |
| **07** | Templates | Generic `Stack<T>` class template supporting `int`, `float`, and `string` types. |
| **08** | Standard Template Library (STL) | Using `vector`, `map`, and algorithms like `sort` and `find_if` on student marks dataset. |
| **09** | Exception Handling | Custom exception hierarchy (`BankingException`, `InsufficientFundsException`, `InvalidAmountException`) with `try-catch`. |
| **10** | File Handling | Reading and writing CSV records using `fstream` and demonstrating file pointers (`tellp`, `tellg`, `seekg`). |
| **11** | Mini Project | Console-based Student Management System with file persistence (`students_db.csv`). |

---

## Directory Structure

```
OOPS_LAB/
├── Experiment_01/
│   └── main.cpp
├── Experiment_02/
│   └── main.cpp
├── Experiment_03/
│   └── main.cpp
├── Experiment_04/
│   └── main.cpp
├── Experiment_05/
│   └── main.cpp
├── Experiment_06/
│   └── main.cpp
├── Experiment_07/
│   └── main.cpp
├── Experiment_08/
│   └── main.cpp
├── Experiment_09/
│   └── main.cpp
├── Experiment_10/
│   ├── main.cpp
│   └── students.csv
└── Experiment_11_Mini_Project/
    ├── main.cpp
    ├── students_db.csv
    └── README.md
```

---

## How to Compile and Run

To run any experiment, open the terminal in the respective experiment folder and run:

```bash
# Example for Experiment 1
cd OOPS_LAB/Experiment_01
g++ main.cpp -o main.exe
.\main.exe

# Example for Mini Project
cd ../Experiment_11_Mini_Project
g++ main.cpp -o main.exe
.\main.exe
```
