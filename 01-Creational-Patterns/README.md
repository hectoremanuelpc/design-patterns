# Creational Patterns in TypeScript

This repository contains examples and explanations of various creational design patterns implemented in TypeScript. Creational design patterns are concerned with the way objects are created, ensuring that the system is independent of how its objects are created, composed, and represented.

## Table of Contents

1. [Introduction](#introduction)
2. [Patterns Covered](#patterns-covered)

-   [Singleton](#singleton)
-   [Factory Method](#factory-method)
-   [Abstract Factory](#abstract-factory)
-   [Builder](#builder)
-   [Immutable](#immutable)
-   [Factory Function](#factory-function)
-   [Prototype](#prototype)

3. [Getting Started](#getting-started)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

Creational patterns provide various object creation mechanisms, which increase flexibility and reuse of existing code. This repository demonstrates how to implement these patterns in TypeScript.

## Patterns Covered

### Singleton

The Singleton pattern ensures that a class has only one instance and provides a global point of access to it.

### Factory Method

The Factory Method pattern defines an interface for creating an object, but lets subclasses alter the type of objects that will be created.

### Abstract Factory

The Abstract Factory pattern provides an interface for creating families of related or dependent objects without specifying their concrete classes.

### Builder

The Builder pattern separates the construction of a complex object from its representation, allowing the same construction process to create various representations.

### Immutable

The Immutable pattern ensures that an object's state cannot be modified after it is created. This pattern is useful for creating objects that are inherently thread-safe and can be shared freely between multiple threads.

### Factory Function

The Factory Function pattern is a simple function that creates and returns objects. It allows for the creation of objects without using the `new` keyword, providing a more functional approach to object creation.

### Prototype

The Prototype pattern is used to create new objects by copying an existing object, known as the prototype. This pattern is useful for creating objects when the cost of creating a new instance is expensive or complex.

## Getting Started

To get started with the examples in this repository, clone with the following:

```bash
git clone https://github.com/hectoremanuelpc/design-patterns.git
cd design-patterns
```

You can then run the examples using:

```bash
deno pattern.ts
```

## Contributing

Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
