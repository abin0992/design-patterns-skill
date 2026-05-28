---
name: design-patterns
description: Use when implementing object-oriented solutions to recurring software design problems - recognize when to apply creational, structural, or behavioral patterns for flexible, reusable code
---

# Design Patterns Skill

## Overview
Design patterns are typical solutions to commonly occurring problems in software design. They are like pre-made blueprints that you can customize to solve a recurring design problem in your code. This skill helps you recognize when to apply the 22 classic design patterns from the "Gang of Four" catalog to create flexible, reusable, and maintainable object-oriented solutions.

## When to Use
Use this skill when:
- You encounter recurring design problems in your object-oriented code
- You need to create flexible systems that can accommodate future changes
- You want to improve code reusability and reduce tight coupling
- You're building systems that require extensibility without modifying existing code
- You need to communicate design solutions using a common vocabulary with team members

## Core Pattern Categories

### Creational Patterns
Deal with object creation mechanisms, trying to create objects in a manner suitable to the situation:
- **Factory Method**: Provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created
- **Abstract Factory**: Lets you produce families of related objects without specifying their concrete classes
- **Builder**: Separates the construction of a complex object from its representation
- **Prototype**: Lets you copy existing objects without making your code dependent on their classes
- **Singleton**: Ensures a class has only one instance and provides a global point of access to it

### Structural Patterns
Explain how to assemble objects and classes into larger structures while keeping these structures flexible and efficient:
- **Adapter**: Allows objects with incompatible interfaces to collaborate
- **Bridge**: Lets you split a large class or a set of closely related classes into two separate hierarchies
- **Composite**: Lets you compose objects into tree structures and work with these structures as if they were individual objects
- **Decorator**: Lets you attach new behaviors to objects by placing them inside special wrapper objects
- **Facade**: Provides a simplified interface to a complex subsystem
- **Flyweight**: Lets you fit more objects into the available amount of RAM by sharing common parts of state
- **Proxy**: Provides a surrogate or placeholder for another object to control access to it

### Behavioral Patterns
Take care of effective communication and the assignment of responsibilities between objects:
- **Chain of Responsibility**: Lets you pass requests along a chain of handlers
- **Command**: Turns a request into a stand-alone object containing all information about the request
- **Iterator**: Lets you traverse elements of a collection without exposing its underlying representation
- **Mediator**: Lets you reduce chaotic dependencies between objects
- **Memento**: Provides the ability to restore an object to its previous state
- **Observer**: Defines a one-to-many dependency between objects
- **State**: Lets an object alter its behavior when its internal state changes
- **Strategy**: Lets you define a family of algorithms, put each in a separate class, and make them interchangeable
- **Template Method**: Defines the skeleton of an algorithm in a superclass but lets subclasses override specific steps
- **Visitor**: Lets you separate algorithms from the objects on which they operate

## Key Design Principles
Design patterns are based on fundamental principles that make software more flexible and maintainable:

1. **Encapsulate What Varies**: Identify aspects of your application that vary and separate them from what stays the same
2. **Program to an Interface, not an Implementation**: Depend on abstractions, not concrete classes
3. **Favor Composition Over Inheritance**: Prefer object composition over class inheritance for code reuse
4. **SOLID Principles**:
   - Single Responsibility Principle: A class should have just one reason to change
   - Open/Closed Principle: Classes should be open for extension but closed for modification
   - Liskov Substitution Principle: Subtypes must be substitutable for their base types
   - Interface Segregation Principle: Clients shouldn't be forced to depend on methods they don't use
   - Dependency Inversion Principle: High-level modules should not depend on low-level modules

## Implementation Approach
1. **Identify the Problem**: Recognize recurring design problems in your code
2. **Select Appropriate Pattern**: Choose a pattern that addresses your specific problem
3. **Apply Pattern Structure**: Follow the pattern's class/object structure and relationships
4. **Ensure Principle Compliance**: Verify your implementation follows core design principles
5. **Test Extensibility**: Confirm your solution allows for future changes without modifying existing code

## Common Applications
- Creating families of related products (Abstract Factory)
- Providing a unified interface to a subsystem (Facade)
- Adding responsibilities to objects dynamically (Decorator)
- Defining algorithms that can be swapped at runtime (Strategy)
- Managing object creation based on conditions (Factory Method)
- Providing controlled access to objects (Proxy)
- Making objects interchangeable (Iterator, Visitor)

## Benefits
- Increased flexibility and reusability
- Improved code maintainability
- Common vocabulary for design communication
- Solutions proven across multiple contexts and languages
- Reduced tight coupling between components
- Better accommodation of future changes

## Verification
When implementing design patterns, verify:
- Does the pattern solve the identified recurring problem?
- Does the implementation follow the pattern's structure exactly?
- Are core design principles (especially encapsulation and composition) followed?
- Can the solution be extended without modifying existing code?
- Does the pattern improve flexibility compared to alternative approaches?

## Real-World Impact
Design patterns have been proven effective across:
- Enterprise software development
- Framework and library creation
- Large-scale system architecture
- Cross-platform application development
- APIs and SDKs requiring extensibility

Use this skill to transform ad-hoc solutions into principled, flexible designs that stand the test of time.