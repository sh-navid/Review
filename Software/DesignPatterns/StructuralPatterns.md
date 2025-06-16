## Structural Patterns
These patterns deal with object composition and typically help ensure that if one part of a system changes, the entire system doesn’t need to change.

- **Adapter**: Enables compatibility between incompatible interfaces, e.g., a 3-pin charger with a 2-pin outlet.
- **Bridge**: Separates an object's interface from its implementation, allowing both to vary independently.
- **Composite**: Composes objects into tree structures to represent part-whole hierarchies, allowing clients to treat individual objects and compositions uniformly.
- **Decorator**: Allows behavior to be added to individual objects, either statically or dynamically, without affecting the behavior of other objects from the same class.
- **Facade**: Provides a simplified interface to a complex subsystem.
- **Flyweight**: Reduces the cost of creating and manipulating a large number of similar objects by sharing their common state.
- **Proxy**: Acts as a surrogate or placeholder, with types including:
    - **Protection Proxy**
    - **Virtual Proxy**
    - **Remote Proxy**: Used for accessing objects in different address spaces.