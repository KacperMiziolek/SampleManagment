# Sample Management System (C++) 🧪📂

![C++](https://img.shields.io/badge/Language-C%2B%2B17-blue)
![Standard Library](https://img.shields.io/badge/STL-Vector%2FRegex-green)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-lightgrey)

> **PL:** Aplikacja konsolowa w C++ do zarządzania bazą próbek, oferująca trwałość danych (zapis do pliku), zaawansowane wyszukiwanie (Regex) oraz ścisłą walidację danych wejściowych.
>
> **EN:** A C++ console application for managing a sample database, featuring data persistence (file I/O), advanced searching (Regex), and robust input validation.

## 📋 About The Project

This project allows users to manage a database of biological/material samples directly from the command line. Unlike simple student projects, this application focuses on **data integrity** and **usability**. It implements a robust validation system to ensure that dates and formats are correct before processing.

It demonstrates proficiency in:
*   **C++ Standard Library (STL):** Usage of vectors, strings, and streams.
*   **Regular Expressions (`<regex>`):** For pattern matching in search and validation.
*   **File I/O (`<fstream>`):** Implementing a custom parser to save and load state from text files.
*   **Input Validation:** Preventing runtime errors by handling invalid user inputs gracefully.

## 🚀 Key Features

*   **CRUD Operations:** Create, Read, Update, and Delete sample records.
*   **Advanced Search:** Filter samples using standard text or **Regular Expressions** (Regex).
*   **Data Persistence:** Automatic saving and loading of data from `database.txt` (or custom files).
*   **Date Validation:** Checks if the entered dates are logical and follow the correct format.
*   **Robust Menu System:** Interactive CLI interface that handles bad inputs without crashing.

## 🛠️ Tech Stack

*   **Language:** C++ (C++17 Standard)
*   **Libraries:** `<iostream>`, `<vector>`, `<fstream>`, `<regex>`, `<string>`
*   **IDE/Tools:** Visual Studio / VS Code / CLion

## ⚙️ Getting Started

To run this project, you need a C++ compiler (GCC, Clang, or MSVC).

### 1. Clone the repository
```bash
git clone https://github.com/KacperMiziolek/SampleManagment.git
cd SampleManagment
