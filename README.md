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
- **Inversion of Control (IoC)**: Often implemented with Dependency Injection.
- **Dependency Inversion Principle**: High-level modules should not depend on low-level modules; both should depend on abstractions.

#### Domain-Driven Design (DDD)
- A methodology and set of principles focused on building software for complex needs by connecting implementation to an evolving model of core business concepts.

### Design Patterns
- **GoF (Gang of Four)**
    - [Creational Patterns](./Software/DesignPatterns/CreationalPatterns.md): Deal with object creation mechanisms.
    - [Structural Patterns](./Software/DesignPatterns/StructuralPatterns.md): Focus on object composition.
    - [Behavioral Patterns](./Software/DesignPatterns/BehavioralPatterns.md): Emphasize communication and interaction between objects.
- [Additional Patterns](./Software/DesignPatterns/AdditionalPatterns.md)

### Software Architecture

#### UI Patterns
- **Model-View-Controller (MVC)**: Separates an application into three main components: Model, View, and Controller.
- **Model-View-Presenter (MVP)**: Similar to MVC, but with Presenter mediating between Model and View.
- **Model-View-ViewModel (MVVM)**: Separates UI development from business logic for clear data binding.
- **VIPER**: Promotes separation of concerns, consisting of View, Interactor, Presenter, Entity, and Routing.

#### Software Architecture Patterns
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

## Artificial Intelligence
- **Domains**
    - **Machine Learning**
    - **Deep Learning**
    - **Natural Language Processing (NLP)**
- **Tools**
- **Libs**
- **Services**

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
