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


### Frameworks

- React
- Angular
- Vue.js
- Spring
- Django
- Flask
- **.NET Core**: A cross-platform framework primarily using C# for various app development.
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

- A methodology and set of principles focused on building software for complex needs by connecting the implementation to an evolving model of the core business concepts.

### Design Patterns
- GoF (Gang of Four)
    - [Creational Patterns](./Software/DesignPatterns/CreationalPatterns.md)
        - These patterns deal with object creation mechanisms, aiming to create objects in a manner suitable to the situation. They abstract the instantiation process, making it more flexible and reusable.

    - [Structural Patterns](./Software/DesignPatterns/StructuralPatterns.md)
        - These patterns focus on object composition, assisting in ensuring that if one part of a system changes, the entire system doesn’t need to change. They facilitate the organization of classes and objects to form larger structures.

    - [Behavioral Patterns](./Software/DesignPatterns/BehavioralPatterns.md)
        - These patterns emphasize communication and interaction between objects. They address how objects interact with one another, focusing on how they operate and react to changes in state, leading to more flexible and efficient interactions.

- [Additional Patterns](./Software/DesignPatterns/AdditionalPatterns.md)

### Software Architecture

#### UI Patterns

- **Model-View-Controller (MVC)**: Separates an application into three main components: the Model (data), the View (user interface), and the Controller (business logic).
- **Model-View-Presenter (MVP)**: Separates the application into three components: the Model, the View, and the Presenter, which mediates between Model and View.
- **Model-View-ViewModel (MVVM)**: Separates UI development from business logic and allows for clear data binding, primarily used in XAML-based technologies.
- **VIPER**: Stands for View, Interactor, Presenter, Entity, and Routing, promoting separation of concerns with clear boundaries between components.

#### Software Architecture Patterns

- **Clean Architecture**: A software design philosophy that separates the software solutions into layers, allowing for independent development, testing, and deployment. Focuses on the business logic and keeps it separated from frameworks and UI.
- **Onion Architecture**: Emphasizes a clear separation of concerns, organizing the system into concentric layers with core business logic at the center.
- **Microkernel Architecture**: Uses a minimal core system with the ability to add plugins or modules for extended functionalities without affecting the core system.
- **Hexagonal Architecture (Ports and Adapters)**: Focuses on separating the application logic from external systems via ports and adapters.

              

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
- Domains
    - **Machine Learning**
    - **Deep Learning**
    - **Natural Language Processing (NLP)**
- Tools
- Libs
- Services

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

### Other
- **n8n**: An open-source workflow automation tool that allows you to connect various services and automate tasks. 
- **Zapier**: A popular automation tool that connects different apps and services; however, it is not open-source and has a pricing model. 
- **Integromat (Make)**: Offers similar capabilities to n8n and Zapier, allowing for automation between services with a visual editor. 
- **Node-RED**: A flow-based development tool for visual programming, allowing for wiring together devices, APIs, and online services. 
- **Apache Airflow**: An open-source tool to programmatically author, schedule, and monitor workflows.
- **BPMN Tools (e.g., Camunda)**: Business Process Model and Notation tools for modeling business processes and automating them. 
