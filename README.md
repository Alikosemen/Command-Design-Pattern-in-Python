# Command Design Pattern

## Definition
The Command Design Pattern encapsulates a request as an object, thereby allowing users to parameterize clients with queues, requests, and operations. It provides the means to separate the responsibilities of issuing commands from the responsibilities of executing commands, enhancing flexibility and control over functionality.

## Implementation Overview
This repository demonstrates the implementation of a switch mechanism using the Command Design Pattern. This pattern allows the switch to be decoupled from the devices it controls (like lamps or engines), making the switch code reusable and extendable.

## Concept
Command Pattern is associated with three components, the client, the invoker, and
the receiver. Let‘s take a look at all the three components.

**Client:** the Client represents the one that instantiates the encapsulated object.

**Invoker:** the Invoker is responsible for deciding when the method is to be
invoked or called.

**Receiver:** the Receiver is that part of the code that contains the instructions to
execute when a corresponding command is given.

## Benefits
- **Separation of Concerns**: Decouples the classes that invoke the operation from the ones that perform the operation.
- **Extensibility**: New commands can be added without changing existing code, following the Open/Closed Principle.
- **Flexibility**: It's easy to add new commands and extend the existing functionality without changing the core code.

Feel free to explore the repository to see how the Command Design Pattern facilitates a flexible and reusable switch mechanism.
