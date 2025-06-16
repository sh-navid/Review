# Review

A guide to review concepts that a software engineer might overlook or forget.

## Artificial Intelligence
- [**Overview**](./AI/AI.md)
- **Tools**
- **Libs**
- **Services**

## Software

### Programming Languages
- JavaScript
- Python
- Java
- C#
- Go
- Ruby
- Kotlin: A modern programming language for Android and server-side applications.
- **Swift**: A language for iOS and macOS app development.
- **Rust**: A systems programming language focused on safety and performance.
- **PHP**: A popular server-side scripting language for web development.
- **TypeScript**: A superset of JavaScript that adds static typing.
- **Scala**: A general-purpose language providing support for functional programming.
- **Elixir**: A dynamic, functional language designed for building scalable and maintainable applications.


### Frameworks
#### Frontend
- React
- Angular
- Vue.js
- Svelte: A modern framework that shifts much of the work to compile time, resulting in fast efficient applications.
- Ember.js: A framework for creating ambitious web applications.

#### Backend
- Spring: A comprehensive framework for enterprise Java.
- Django: A high-level Python web framework.
- Flask: A lightweight Python web framework for building APIs.
- .NET Core: A cross-platform framework primarily using C# for various app development.
    - **ASP.NET Core**: For web applications and APIs, leveraging MVC and REST principles.
- Express.js: A minimal and flexible Node.js web application framework.
- Ktor: A framework for building asynchronous servers and clients.
- Ruby on Rails: A web application framework written in Ruby.
- Laravel: A PHP framework for building web applications with expressive syntax.

#### Fullstack
- Meteor: A full-stack platform for building web and mobile applications in pure JavaScript.
- Next.js: A React-based framework that enables functionality such as server-side rendering and generating static websites.
- Nuxt.js: A framework for building Vue.js applications with powerful routing and server-side rendering capabilities.


### Programming Paradigms
- **Object-Oriented Programming (OOP)**: A paradigm based on the concept of "objects", which can contain data and code: data in the form of fields (attributes) and code in the form of procedures (methods). OOP allows for encapsulation, inheritance, and polymorphism, making it easier to manage large codebases.
  
- **Functional Programming**: A paradigm that treats computation as the evaluation of mathematical functions and avoids changing state or mutable data. It emphasizes functions as first-class citizens, enabling higher-order functions, and promotes immutability, making code easier to reason about.

- **Procedural Programming**: A paradigm built around the concept of procedure calls, where programs are structured as a sequence of instructions/actions. It focuses on the idea of procedure or routine calls, leading to organized and modular code.

- **Aspect-Oriented Programming (AOP)**: A paradigm that aims to increase modularity by allowing the separation of cross-cutting concerns (such as logging, security, etc.) from business logic. AOP enables the definition of aspects that can be applied to various parts of a program without cluttering the core logic.

- **Reactive Programming**: A paradigm concerned with data streams and the propagation of change. It allows for asynchronous programming, where components react to changes or events, making it suitable for event-driven applications.

- **Context-Oriented Programming**: This paradigm focuses on the runtime environment and how certain behaviors can change depending on the context. It allows developers to define different sets of behaviors that can be activated or deactivated based on the current context, facilitating more adaptive software.

- **Logic Programming**: A paradigm based on formal logic. Programs are written as a set of sentences in logical form, expressing facts and rules about some problem domain. Prolog is a common language used in this paradigm.

- **Declarative Programming**: A paradigm where the focus is on what the program should accomplish rather than detailing the control flow. This includes subparadigms like SQL for database queries, where users specify the desired result without explicitly defining the steps to achieve it.

- **Event-Driven Programming**: A paradigm where the flow of the program is determined by events such as user actions (clicks, key presses) or messages from other programs. It's widely used in graphical user interfaces and real-time systems.

- **Concurrent Programming**: A paradigm that deals with the execution of multiple instruction sequences at the same time. It allows for parallel execution, which can improve performance on multi-core processors and handle processes that may be waiting for external resources.

- **Distributed Programming**: A paradigm focused on structuring software as multiple processes that run on different machines and communicate over a network. It allows for building applications that can scale across multiple servers, providing redundancy and complexities associated with network communications.


### Software Design Principles

#### Object-Oriented Principles
- **SOLID**: A set of five principles for object-oriented programming that helps create software that is easy to maintain and extend:
  - **Single Responsibility Principle (SRP)**: A class should have only one reason to change, meaning it should only have one job or responsibility. This simplifies the code and enhances maintainability.
  - **Open/Closed Principle (OCP)**: Software entities should be open for extension but closed for modification. New functionality should be added by creating new code rather than altering existing code.
  - **Liskov Substitution Principle (LSP)**: Objects of a superclass should be replaceable with objects of a subclass without affecting the correctness of the program.
  - **Interface Segregation Principle (ISP)**: Clients should not be forced to depend on interfaces they do not use. This encourages the creation of smaller, more specific interfaces.
  - **Dependency Inversion Principle (DIP)**: High-level modules should not depend on low-level modules; both should depend on abstractions. This principle helps to decouple dependencies in software design.

- **GRASP (General Responsibility Assignment Software Patterns)**: A set of nine principles for assigning responsibilities to classes and objects in object-oriented design. Key principles include Information Expert, Creator, and Controller.

- **KISS (Keep It Simple, Stupid)**: Emphasizes the importance of simplicity in design and avoiding unnecessary complexity.

- **DRY (Don't Repeat Yourself)**: Advocates for reducing the repetition of code by abstracting shared functionality into single definitions.

- **YAGNI (You Aren't Gonna Need It)**: A principle advocating that developers should not add functionality until it is necessary, thereby preventing overengineering.

- **Separation of Concerns (SoC)**: Different concerns should be managed separately to reduce complexity. This principle organizes code into distinct sections, allowing each section to focus on a specific concern.

- **Law of Demeter (LoD)**: Also known as the principle of least knowledge, it suggests that an object should only interact with its immediate collaborators and not with objects that it knows indirectly.

- **Composition over Inheritance**: Advocates for using composition to achieve code reuse rather than relying on class inheritance. It promotes flexibility and easier maintenance.

- **Fail Fast**: Suggests that a system should immediately report any condition that is likely to indicate an error, allowing developers to catch issues as early as possible.

#### General Design Principles
- **Inversion of Control (IoC)**: This design principle dictates that the control of object creation and binding should be transferred to a container or framework, commonly implemented with Dependency Injection.

#### Domain-Driven Design (DDD)
- A methodology focused on designing complex software systems by connecting implementation to an evolving model of core business concepts. DDD emphasizes collaboration between technical and domain experts to refine a shared understanding of the business requirements.



### Design Patterns
- **GoF (Gang of Four)**
    - [Creational Patterns](./Software/DesignPatterns/CreationalPatterns.md): Deal with object creation mechanisms.
    - [Structural Patterns](./Software/DesignPatterns/StructuralPatterns.md): Focus on object composition.
    - [Behavioral Patterns](./Software/DesignPatterns/BehavioralPatterns.md): Emphasize communication and interaction between objects.
- [Additional Patterns](./Software/DesignPatterns/AdditionalPatterns.md)

### Software Architecture

- UI Patterns
    - **Model-View-Controller (MVC)**: Separates an application into three main components: Model, View, and Controller.
    - **Model-View-Presenter (MVP)**: Similar to MVC, but with Presenter mediating between Model and View.
    - **Model-View-ViewModel (MVVM)**: Separates UI development from business logic for clear data binding.
    - **VIPER**: Promotes separation of concerns, consisting of View, Interactor, Presenter, Entity, and Routing.

- Software Architecture Patterns
    - **Clean Architecture**: Separates software solutions into layers focusing on business logic.
    - **Onion Architecture**: Organizes the system into concentric layers with core business logic at the center.
    - **Microkernel Architecture**: Minimal core system with the ability to add plugins for extended functionalities.
    - **Hexagonal Architecture (Ports and Adapters)**: Separates application logic from external systems.

### Web API Architecture
- **REST**
- **SOAP**
- **GraphQL**
- **gRPC**
- **Apache Kafka**
- **AsyncAPI**
- **Remote Procedure Call (RPC)**

## Databases

### SQL Databases
- **MySQL**: An open-source relational database management system.
- **PostgreSQL**: A powerful, open-source object-relational database system with an emphasis on extensibility and standards compliance.
- **SQLite**: A self-contained, high-reliability, embedded SQL database engine.

### NoSQL Databases
- **MongoDB**: A popular NoSQL database that stores data in JSON-like documents.
- **Cassandra**: A highly scalable NoSQL database designed for handling large amounts of data across many servers with no single point of failure.
- **Redis**: An open-source, in-memory data structure store, used as a database, cache, and message broker.

### Database Concepts
- **ORM (Object-Relational Mapping)**: A programming technique for converting data between incompatible type systems in object-oriented programming languages.
- **Database Indexing**: A data structure technique that shows the efficiency of data retrieval operations on a database table.
- **ACID Properties**: Set of properties that guarantee database transactions are processed reliably.

### Database Design Principles
- **Normalization**: Process of organizing fields and tables of a relational database to minimize redundancy.
- **Denormalization**: The process of attempting to optimize the read performance of a database by adding redundant data.


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
- **Test-Driven Development (TDD)**: Writing tests before the code.

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
- **Service Mesh**: Infrastructure layer for handling service-to-service communication.
- **API Management**

## Other Topics

### Frontend Development
- **CSS**
- **Progressive Web Apps (PWA)**
- **Markdown**

### Source Control Systems
- **Git**
- **SVN**
- **TFS**

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

### Other
- **n8n**: An open-source workflow automation tool.
- **Zapier**: Automation tool with a pricing model.
- **Integromat (Make)**: Similar capabilities to n8n and Zapier.
- **Node-RED**: A flow-based development tool for visual programming.
- **Apache Airflow**: Open-source tool for authoring, scheduling, and monitoring workflows.
- **BPMN Tools (e.g., Camunda)**: Business Process Model and Notation tools for modeling business processes.
