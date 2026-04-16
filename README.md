# Semester Mark Tree Calculator

A Java program that uses a **General Tree** data structure to represent and calculate a student's semester mark based on weighted assessment components.

**Author:** DN MBOYI  
**Student Number:** 222019179  
**Assignment:** General Tree Implementation  
**Course:** CSC03B3 (Data Structures / Java Programming)

---

## Project Description

This application models a student's semester mark structure as a **tree**, where:
- The **root** represents the overall semester mark (e.g., CSC3A)
- **Internal nodes** represent weighted sections (ST, MP, CT+PA)
- **Leaf nodes** represent individual marks

The program calculates the final semester mark using **weighted averages** recursively.

### Tree Structure Example:

CSC3A 100
ST 50
87
92
MP 25
78
CT+PA 25
CT 50
65
72
81
PA 50
55
68


---

## Features

- **General Tree** implementation (`Tree<T>`)
- `TreeNode<T>` implementing `Position<T>`
- Support for adding children to any node
- Preorder traversal with proper indentation
- Recursive calculation of weighted semester mark (`calcSM`)
- Depth calculation and internal node checking
- Custom `Mark` class for assessment components

---

## Files Included

- `Main.java` – Main program with tree construction and semester mark calculation
- `Tree.java` – General Tree implementation
- `TreeNode.java` – Tree node class implementing `Position`
- `Position.java` – Position interface
- `Mark.java` – Custom class for assessment name and value

---

## Technologies Used

- **Tree Data Structure** (General Tree)
- **Recursion** (for weighted mark calculation and traversal)
- **Iterator Pattern** for children traversal
- **Object-Oriented Design**
- **Position ADT**

---

## How to Run

### Compile and Run:
```bash
javac *.java
java Main
