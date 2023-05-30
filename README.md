# SOLID Design Principles in Golang

This repository provides practical examples demonstrating the SOLID design principles in Golang. Each design principle is illustrated using an individual example, and a combined example showcases all the principles together.


## Table of Contents

1. [Introduction](#introduction)
2. [Single Responsibility Principle (SRP)](#single-responsibility-principle-srp)
3. [Open/Closed Principle (OCP)](#openclosed-principle-ocp)
4. [Liskov Substitution Principle (LSP)](#liskov-substitution-principle-lsp)
5. [Interface Segregation Principle (ISP)](#interface-segregation-principle-isp)
6. [Dependency Inversion Principle (DIP)](#dependency-inversion-principle-dip)
7. [Combined SOLID Example](#combined-solid-example)

## Introduction

The SOLID design principles are a set of guidelines for writing maintainable, scalable, and robust software. They were first introduced by Robert C. Martin and have since become an essential part of object-oriented software design. These principles apply to other programming paradigms as well.

In this repository, you'll find Golang examples illustrating the application of each SOLID design principle, as well as a comprehensive example that combines all principles.

## Single Responsibility Principle (SRP)

The Single Responsibility Principle states that a class or module should have only one reason to change, meaning it should have a single responsibility or job. This principle encourages separating concerns, making the codebase easier to understand, maintain, and extend.

*Example: See [example-srp.go](./src/example-srp.go)*

## Open/Closed Principle (OCP)

The Open/Closed Principle states that software entities (classes, modules, functions, etc.) should be open for extension but closed for modification. This entails adding new features or modifying existing behaviors without changing existing code, typically accomplished through abstract classes, interfaces, or other forms of polymorphism.

*Example: See [example-ocp.go](./src/example-ocp.go)*

## Liskov Substitution Principle (LSP)

The Liskov Substitution Principle states that objects of a derived/child class should be able to replace objects of the base/parent class without affecting the correctness of the program. Essentially, subclasses should maintain the properties of their parent classes to ensure consistent behavior throughout the code.

*Example: See [example-lsp.go](./src/example-lsp.go)*

## Interface Segregation Principle (ISP)

The Interface Segregation Principle states that clients should not be forced to rely on interfaces they don't use. To achieve this, larger interfaces should be broken down into smaller, focused interfaces so clients only need to be aware of and implement relevant methods.

*Example: See [example-isp.go](./src/example-isp.go)*

## Dependency Inversion Principle (DIP)

The Dependency Inversion Principle entails depending on abstractions rather than concrete implementations. High-level modules should not rely on low-level modules; both should depend on abstractions. Moreover, abstractions shouldn't depend on details; details should depend on abstractions. Adhering to DIP creates more reusable, flexible, and maintainable code.

*Example: See [example-dip.go](./src/example-dip.go)*

## Combined SOLID Example

This comprehensive example demonstrates the application of all SOLID design principles within a single Golang program.

*Example: See [example-solid.go](./src/example-solid.go)*

Feel free to explore each example to deepen your understanding of the SOLID design principles in Golang. Happy coding!
