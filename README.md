# Object-Oriented Programming with C++ - Unit III

## Polymorphism - Practical Programs

### Student Details

**Student Name:** Aditya Prabhakar Bhore  
**PRN:** 125UAD1103  
**Class/Division:** SY B.Tech AI&DS: F 
**Course:** Object-Oriented Programming with C++  
**Course Code:** ADPC303  
**Unit:** Unit III - Polymorphism  
**Language Standard:** C++

---

## About This Repository

This repository contains practical C++ programs for Unit III:
**Polymorphism** of Object-Oriented Programming with C++.

The programs demonstrate function overloading, operator overloading,
run-time polymorphism, virtual functions, pure virtual functions,
abstract classes, base-class pointers and references, virtual
destructors and object slicing.

---

# List of Programs

## 1. Function Overloading

This program demonstrates compile-time polymorphism using
function overloading.

It uses multiple `add()` functions with different parameter
lists for integers, doubles and three integer values.

---

## 2. Area Calculator Using Function Overloading

This program calculates the area of different shapes using
overloaded functions.

It calculates the area of a square, rectangle and circle using
different parameter lists.

---

## 3. Unary Minus Operator Overloading

This program demonstrates unary operator overloading.

The unary minus operator is overloaded to obtain the negative
value of an object.

---

## 4. Prefix and Postfix Increment Operator Overloading

This program demonstrates prefix and postfix increment
operator overloading.

It shows the difference between `++object` and `object++`
using a Counter class.

---

## 5. Binary + Operator Overloading for Complex Numbers

This program demonstrates binary operator overloading using
the `+` operator.

It adds two complex number objects using an overloaded
`operator+()` function.

---

## 6. Relational Operator Overloading

This program demonstrates relational operator overloading.

The `>` operator is overloaded to compare two Distance objects.

---

## 7. Friend / Non-Member Operator Overloading

This program demonstrates operator overloading using a
friend non-member function.

It allows an expression such as `10 + complexNumber` by using
a friend operator function.

---

## 8. Base Pointer Without a Virtual Function

This program demonstrates static binding using a base-class
pointer.

Since the base function is not virtual, the base-class version
of the function is called.

---

## 9. Base Pointer With a Virtual Function

This program demonstrates run-time polymorphism using a
virtual function and a base-class pointer.

The base pointer can point to different derived objects and
the correct derived function is selected during execution.

---

## 10. Base Reference With a Virtual Function

This program demonstrates run-time polymorphism using a
base-class reference.

The program processes Rectangle and Circle objects through
a common Shape reference.

---

## 11. Abstract Class and Pure Virtual Function

This program demonstrates the use of an abstract class.

The `Shape` class contains a pure virtual `area()` function,
which must be implemented by derived classes.

---

## 12. Collection of Polymorphic Shape Pointers

This program demonstrates polymorphic processing using a
collection of shape pointers.

It uses `std::unique_ptr` and a vector to store different
derived Shape objects.

---

## 13. Virtual Destructor

This program demonstrates the importance of a virtual destructor
when deleting a derived object through a base-class pointer.

It ensures that both derived and base destructors are executed.

---

## 14. Object Slicing Demonstration

This program demonstrates object slicing.

It shows the difference between passing a derived object
by value and passing it by reference.

---

# Mini-Projects

## 15. Payment Processing System

This mini-project implements a real-world polymorphic payment
system.

It supports different payment methods such as Card Payment,
UPI and Net Banking.

The program demonstrates abstract classes, pure virtual
functions, derived classes, base references and run-time
polymorphism.

---

## 16. Employee Payroll Mini-Project

This mini-project develops a salary calculation system using
abstract classes and run-time polymorphism.

It supports Permanent Employees and Contract Employees.

The program calculates salary using overridden
`calculateSalary()` functions.

---

# OOP Concepts Covered

- Introduction to Polymorphism
- Compile-Time Polymorphism
- Run-Time Polymorphism
- Function Overloading
- Operator Overloading
- Unary Operator Overloading
- Binary Operator Overloading
- Prefix Operator Overloading
- Postfix Operator Overloading
- Relational Operator Overloading
- Friend Operator Function
- Virtual Functions
- Function Overriding
- Base-Class Pointers
- Base-Class References
- Pure Virtual Functions
- Abstract Classes
- Virtual Destructors
- Object Slicing
- Polymorphic Collections

---

# Repository Structure

```text
OOP-cpp-Unit-III-Polymorphism
│
├── README.md
│
├── 01-Function-Overloading
│   └── function_overloading.cpp
│
├── 02-Area-Calculator
│   └── area_calculator.cpp
│
├── 03-Unary-Minus-Operator
│   └── unary_minus_operator.cpp
│
├── 04-Prefix-Postfix-Increment
│   └── prefix_postfix_increment.cpp
│
├── 05-Complex-Number-Addition
│   └── complex_number_addition.cpp
│
├── 06-Relational-Operator
│   └── relational_operator.cpp
│
├── 07-Friend-Operator-Overloading
│   └── friend_operator_overloading.cpp
│
├── 08-Base-Pointer-Without-Virtual
│   └── base_pointer_without_virtual.cpp
│
├── 09-Base-Pointer-With-Virtual
│   └── base_pointer_with_virtual.cpp
│
├── 10-Base-Reference-With-Virtual
│   └── base_reference_with_virtual.cpp
│
├── 11-Abstract-Class
│   └── abstract_class.cpp
│
├── 12-Polymorphic-Shape-Pointers
│   └── polymorphic_shape_pointers.cpp
│
├── 13-Virtual-Destructor
│   └── virtual_destructor.cpp
│
├── 14-Object-Slicing
│   └── object_slicing.cpp
│
├── 15-Payment-Processing-System
│   └── payment_processing_system.cpp
│
└── 16-Employee-Payroll
    └── employee_payroll.cpp
