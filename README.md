# Review
A guide to review concepts that a software engineer might overlook or forget.

## Software

### Programming Languages
- JavaScript
- Python
- Java
- C#
- Go
- Ruby
- **Kotlin**: A modern programming language for Android and server-side applications.
- **.NET Core**: A cross-platform framework primarily using C# for various app development.

### Frameworks
- React
- Angular
- Vue.js
- Spring
- Django
- Flask
- **ASP.NET Core**: For web applications and APIs, leveraging MVC and REST principles.
- **Ktor**: A framework for building asynchronous servers and clients.

### Programming Paradigms
- Object-Oriented Programming (OOP)
- Functional Programming
- Procedural Programming
- Aspect-Oriented Programming (AOP)
- Reactive Programming
- Context-Oriented Programming

### Software Design Principles
#### Object-Oriented Principles
- **SOLID**: A set of principles that helps design software that is easy to maintain and extend.
- **GRASP**: General Responsibility Assignment Software Patterns.
- **KISS**: Keep It Simple, Stupid.
- **DRY**: Don't Repeat Yourself.
- **YAGNI**: You Aren't Gonna Need It.
- **CLARITY**

#### General Design Principles
- **Inversion of Control (IoC)**: A principle often implemented with Dependency Injection.
- **Dependency Inversion Principle**: High-level modules should not depend on low-level modules; both should depend on abstractions.

#### Domain-Driven Design (DDD)
- **Domain-Driven Design (DDD)**: A methodology and set of principles focused on building software for complex needs by connecting the implementation to an evolving model of the core business concepts.


### Design Patterns

## Creational Patterns
These patterns deal with object creation mechanisms, trying to create objects in a manner suitable to the situation.

- **Singleton**: Ensures a class only has one instance and provides a global point of access to it.
- **Factory Method**: Defines an interface for creating an object but lets subclasses alter the type of objects that will be created.
- **Abstract Factory**: Creates an interface for creating families of related or dependent objects without specifying their concrete classes.
- **Builder**: Separates the construction of a complex object from its representation, allowing the same construction process to create different representations.
- **Prototype**: Involves creating an object based on a template of an existing object through cloning.

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

## Behavioral Patterns
These patterns focus on communication between objects, what goes on between objects and how they operate, along with how they react to changes.

- **Observer**: A pattern for notifying multiple subscribers about a state change.
- **Strategy**: Enables selecting an algorithm at runtime by defining a family of algorithms, encapsulating each one, and making them interchangeable.
- **Command**: Encapsulates a request as an object, thereby allowing for parameterization of clients with queues, requests, and operations.
- **Chain of Responsibility**: Passes a request along a chain of handlers, allowing multiple objects an opportunity to handle the request.
- **Memento**: Captures and externalizes an object’s internal state without violating encapsulation, allowing the object to be restored to this state later.
- **Iterator**: Provides a way to access the elements of an aggregate object without exposing its underlying representation.
- **State**: Allows an object to alter its behavior when its internal state changes.
- **Template Method**: Defines the skeleton of an algorithm in the superclass but lets subclasses redefine certain steps.
- **Visitor**: Lets you separate algorithms from the object structure on which it operates.

## Additional Patterns
These patterns don’t fit neatly into the categories above but are still important in software design.

- **Dependency Injection (DI)**: A technique whereby one object supplies the dependencies of another object.
- **Service Locator Pattern**: A design pattern that intends to allow for the resolution of dependencies across the application.

### Software Architecture
- **Model-View-Controller (MVC)**
- **Model-View-Presenter (MVP)**
- **Model-View-ViewModel (MVVM)**
- **VIPER**
- **Clean Architecture**
- **Hexagonal Architecture (Ports and Adapters)**

### Web API Architecture
- **REST**
- **SOAP**
- **GraphQL**
- **gRPC**
- **Apache Kafka**
- **AsyncAPI**
- **Remote Procedure Call (RPC)**

## Network
- [Network Protocols](./Network/Protocols.md)
- [Network Tools](./Network/Tools.md)

## Security
- [OWASP Top 10](./Security/OWASP.md)
- **RSA**: Asymmetric cryptographic algorithm.
- **JWT**: JSON Web Tokens for secure data transmission.
- **OAuth**: Delegated access management for services.
- **SSO**: Single Sign-On for user authentication.
- **Network Security**: Protecting the integrity and usability of networks.
- **Application Security**: Measures to improve the security of applications.

## DevOps
### CI/CD Pipelines
- **GitHub Actions**
- **GitLab CI/CD**
- **Jenkins**
- **Travis CI**
- **CircleCI**

### Testing Strategies
- **Unit Testing**
- **Integration Testing**
- **Architecture Testing**
- **Linting**: Checking code for stylistic errors.
- **Dependency Checks**
- **Test-Driven Development (TDD)**: A software development approach where tests are written before the code, guiding the development process and ensuring the code meets requirements.


## Containers
- **Containerization**
    - **Docker**
    - **Docker Swarm**
- **Orchestration**
    - **Kubernetes**

## Cloud Platforms
- **AWS**
- **Azure**
- **Google Cloud Platform (GCP)**
- **Multi-Cloud Strategies**

## Log Management Tools
- **Grafana**
- **ELK Stack**: Elasticsearch, Logstash, and Kibana.
- **Splunk**
- **Prometheus**

## Configuration Management Tools
- **Puppet**
- **SaltStack**
- **Ansible**
- **Chef**

## Essential Concepts
- **Microservices**: Architecture style that structures an application as a collection of loosely coupled services.
- **Service Mesh**: Dedicated infrastructure layer for handling service-to-service communication.
- **API Management**

## Artificial Intelligence
- **Machine Learning**
- **Deep Learning**
- **Natural Language Processing (NLP)**

## Other Topics

### Frontend Development
- **CSS**
- **Progressive Web Apps (PWA)**
- **Markdown**

### Source Control Systems
- **Git**
- **SVN**

### API Tools
- **Postman**
- **Curl**

### Infrastructure as Code
- **Terraform**

### Text Editors & Command Line Tools
- **Vim**
- **Bash**
- **SSH**

### Messaging & Concurrency
- **Message Brokers**
    - **RabbitMQ**
    - **Apache Kafka**
- **Coroutines**
- **Asynchronous Programming**
