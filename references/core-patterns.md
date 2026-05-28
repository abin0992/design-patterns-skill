# Core Pattern Categories

## Creational Patterns
Deal with object creation mechanisms, trying to create objects in a manner suitable to the situation:
- **Factory Method**: Provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created
- **Abstract Factory**: Lets you produce families of related objects without specifying their concrete classes
- **Builder**: Separates the construction of a complex object from its representation
- **Prototype**: Lets you copy existing objects without making your code dependent on their classes
- **Singleton**: Ensures a class has only one instance and provides a global point of access to it

## Structural Patterns
Explain how to assemble objects and classes into larger structures while keeping these structures flexible and efficient:
- **Adapter**: Allows objects with incompatible interfaces to collaborate
- **Bridge**: Lets you split a large class or a set of closely related classes into two separate hierarchies
- **Composite**: Lets you compose objects into tree structures and work with these structures as if they were individual objects
- **Decorator**: Lets you attach new behaviors to objects by placing them inside special wrapper objects
- **Facade**: Provides a simplified interface to a complex subsystem
- **Flyweight**: Lets you fit more objects into the available amount of RAM by sharing common parts of state
- **Proxy**: Provides a surrogate or placeholder for another object to control access to it

## Behavioral Patterns
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