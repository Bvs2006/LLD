# Low-Level Design (LLD) Roadmap

A practical roadmap to learn and practice Low-Level Design using
OOP, SOLID principles, Design Patterns, UML, and real-world problems.

---

## 1. OOP Fundamentals

Before LLD, make sure you understand these properly.

- [x] Classes and Objects
- [x] Constructors
- [x] Instance Variables
- [x] Methods
- [x] Encapsulation
- [x] Abstraction
- [x] Inheritance
- [x] Polymorphism
- [x] Method Overloading
- [x] Method Overriding
- [x] Access Modifiers
- [x] Abstract Classes
- [x] Interfaces
- [x] Composition
- [x] Aggregation
- [x] Association
- [x] Dependency

### Practice

- [ ] Bank Account
- [ ] Student Management System
- [ ] Library Management System
- [ ] Employee Management System

---

# 2. OOP Design Principles

Understand how to design classes properly.

## Class Design

- [ ] High Cohesion
- [ ] Low Coupling
- [ ] Encapsulation
- [ ] Separation of Concerns
- [ ] Favor Composition over Inheritance
- [ ] Program to an Interface
- [ ] Dependency Injection

## Important Questions

- [ ] What should be a class?
- [ ] What should be an attribute?
- [ ] What should be a method?
- [ ] Which class owns the responsibility?
- [ ] Which class should depend on another class?
- [ ] Should I use inheritance or composition?

---

# 3. SOLID Principles

This is one of the most important parts of LLD.

- [ ] S — Single Responsibility Principle
- [ ] O — Open/Closed Principle
- [ ] L — Liskov Substitution Principle
- [ ] I — Interface Segregation Principle
- [ ] D — Dependency Inversion Principle

## Practice

For every principle:

- [ ] Understand the violation
- [ ] Identify the problem
- [ ] Refactor the design
- [ ] Write code
- [ ] Explain why the new design is better

---

# 4. Relationships Between Classes

Learn how classes interact.

- [ ] Association
- [ ] Aggregation
- [ ] Composition
- [ ] Dependency
- [ ] Inheritance
- [ ] Realization

### Example

```text
Car -------- Engine
       has-a

Dog -------- Animal
       is-a

Order ------> PaymentService
       uses
