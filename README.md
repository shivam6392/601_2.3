# Java Streams & Lambda Expressions Project

This project demonstrates the use of **Java Lambda Expressions**, **Streams API**, and **Collections** with a console-based menu system.

## 📁 Project Structure

```
Main.java  
├── class Employee  
├── class Student  
├── class Product  
└── public class Main
```

## ✅ Features

### 1. Sort Employees using Lambda Expressions
- Takes user input for employee details.
- Sorts employees by:
  - Name (A–Z)
  - Age (Ascending)
  - Salary (Descending)

### 2. Filter & Sort Students using Streams
- Accepts student name and marks.
- Displays:
  - Original list
  - Students scoring above 75%, sorted by marks.

### 3. Process Product Dataset using Streams
- Inputs product name, price, and category.
- Displays:
  - Original list of products  
  - Products grouped by category  
  - Most expensive product in each category  
  - Average price of all products

## 🧠 Concepts Used

| Concept                         | Description |
|----------------------------------|-------------|
| Lambda Expressions              | Custom sorting logic |
| Streams API                     | Filter, sort, map, group, aggregate operations |
| Collectors                      | groupingBy, maxBy, averagingDouble |
| Optional, Map, List            | Data structures and safe value handling |
| Scanner Input                  | User interaction |

## ▶️ How to Run

### Compile:
```bash
javac Main.java
```

### Run:
```bash
java Main
```

### Menu:
```
========= MENU =========
1. Sort Employees using Lambda Expressions
2. Filter and Sort Students using Streams
3. Process Product Dataset using Stream Operations
4. Exit
```

## 📌 Future Enhancements
- File storage for results  
- Input validation and exception handling  
- GUI using JavaFX or Swing  
- Database support using JDBC

## 📜 Author
Developed with ❤️ using Java.
