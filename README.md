# ⚙️ Backend Libraries & Tools

Welcome! 👋

This repository contains a collection of **Backend Libraries and Tools** built with **JavaScript and Node.js**, focusing on implementing core backend concepts, data structures, algorithms, and reusable components from scratch.

The goal is to strengthen my **Software Engineering skills** by building practical tools, understanding their internal implementations, analyzing performance trade-offs, and designing reliable, maintainable, and efficient software.

Rather than relying entirely on ready-made libraries, these projects emphasize understanding **how things work internally**, why specific design decisions are made, and how to implement solutions correctly.

---

## 🛠️ Concepts & Technologies

### 🧠 Backend Engineering

- Node.js and JavaScript
- Express.js and HTTP Fundamentals
- API Design and Reusable Components
- Error Handling and Input Validation
- Separation of Concerns
- Clean Code and Maintainable Architecture
- KISS and YAGNI Principles

### 📚 Data Structures & Algorithms

- Hash Maps
- Doubly Linked Lists
- Min-Heaps and Priority Queues
- Time and Space Complexity
- Efficient Data Access and Updates
- Algorithmic Trade-offs
- Choosing Appropriate Data Structures

### 🏗️ System Design & Backend Concepts

- Caching Strategies
- Time-to-Live (TTL) and Expiration Policies
- Rate Limiting Algorithms
- Resource Management
- Concurrency and Shared-State Considerations
- Performance Optimization
- Reliability and Edge Case Handling

### 🧪 Testing & Code Quality

- Jest
- Unit Testing
- Edge Case Testing
- Boundary Value Testing
- Test-Driven Development (TDD) Concepts
- Modular and Testable Code

### 🐳 Tools & Technologies

- JavaScript (ES Modules)
- Node.js
- Express.js
- Jest
- Git & GitHub
- Docker
- Markdown
- UML and Technical Documentation, where appropriate

---

## 📂 Projects

### 1. 🗄️ LRU Cache

🔗 **View Project:** [LRU Cache](https://github.com/Mostafa-36/lru-cache)

A **Least Recently Used (LRU) Cache** implementation that stores frequently accessed data and automatically evicts the least recently used entry when the cache reaches its capacity.

The implementation combines a **Hash Map** and a **Doubly Linked List** to support efficient cache operations.

**Key Concepts:**

- LRU Eviction Policy
- Hash Maps and Doubly Linked Lists
- \(O(1)\) Average-Time Complexity for Core Cache Operations
- Data Structure Design
- Unit Testing with Jest
- Docker Containerization

---

### 2. ⏳ TTL Cache

🔗 **View Project:** [TTL Cache](https://github.com/Mostafa-36/ttl-cache)

A **Time-to-Live (TTL) Cache** implementation that allows entries to expire automatically after a specified duration.

The implementation uses a **Map** for efficient key-based access and a **Min-Heap** to organize entries by expiration time. It combines lazy expiration checks with a periodic cleanup worker to manage expired entries.

**Key Concepts:**

- TTL and Expiration Management
- Map and Min-Heap
- Lazy Expiration
- Periodic Cleanup
- Expiration Scheduling
- Unit Testing with Jest
- Docker Containerization

---
### 3. 📦 ES Modules Deep Dive in Node.js

🔗 View Project: [ES Modules Deep Dive](https://github.com/Mostafa-36/es-modules-demo)

A hands-on **Node.js ES Modules** project focused on understanding how Node.js loads, links, resolves, and executes modules internally, based on Chapter 2 of Node.js Design Patterns.

The project explores module exports and imports, module resolution, circular dependencies, and the ES Module lifecycle, providing a deeper understanding of how Node.js manages dependencies beyond basic syntax.

**Key Concepts:**

- Named, Default & Mixed Exports
- Module Identifiers & Resolution Algorithm
- ES Module Lifecycle (Parsing, Instantiation & Evaluation)
- Circular Dependencies
- Module Scope & Live Bindings
- Node.js Core & Third-Party Modules
- Dependency Management & Dependency Hell
- JavaScript Modules with Chalk

---
### 4. ⚙️ File Processor — Node.js Core Concepts

🔗 View Project: [File Processor](https://github.com/Mostafa-36/File-Processor)

A hands-on Node.js Core Concepts project focused on understanding how Node.js handles blocking and non-blocking I/O, asynchronous execution, and event-driven architecture. Inspired by Chapter 1 of Node.js Design Patterns, the project includes a custom Reactor Pattern simulator to demonstrate how the Event Loop and libuv coordinate asynchronous operations.

**Key Concepts:**

- Blocking & Non-blocking I/O
- Event Loop & Asynchronous Execution
- Reactor Pattern Simulation
- libuv & Thread Pool
- Event Queue & Event Handlers
- Node.js Concurrency & Scalability
- File System Operations
- Event-Driven Architecture

---

## 🔜 Future Projects

More backend libraries and tools will be added as the repository grows.

Potential areas of exploration include:

- Caching and Cache Eviction Strategies
- Rate Limiting and Request Control
- Retry Mechanisms and Exponential Backoff
- Task Queues and Job Scheduling
- Concurrency Control and Synchronization
- Other Reusable Backend Components as the Learning Roadmap Evolves

Each project is selected to practice specific engineering concepts and solve meaningful technical problems rather than simply increase the number of repositories.

---

## 🎯 Why This Repository?

The goals of this repository are to:

- 🧠 Strengthen my Software Engineering fundamentals.
- 🏗️ Understand how backend tools and libraries work internally.
- 📚 Apply appropriate data structures and algorithms to practical problems.
- ⚖️ Evaluate performance, complexity, and architectural trade-offs.
- 🧪 Develop reliable software through systematic testing.
- 🐳 Gain practical experience with Docker and containerized applications.
- 📖 Improve technical documentation and communicate design decisions clearly.
- 💼 Build a portfolio that demonstrates practical engineering skills and supports my Software Engineer interview preparation.

---

## 🚀 Development Workflow

Each project follows a structured development process:

1. **Requirements & Scope** — Define the problem, objectives, and project boundaries.
2. **Concept Review** — Study the relevant data structures, algorithms, and engineering concepts.
3. **API Design** — Define the public interface and expected behavior.
4. **Architecture & Implementation** — Design the internal components and implement the solution.
5. **Testing** — Write Jest tests covering normal behavior, edge cases, and boundary conditions.
6. **Code Review & Complexity Analysis** — Evaluate correctness, maintainability, and time and space complexity.
7. **Documentation** — Document the project's purpose, API, implementation, and design decisions.
8. **Docker** — Containerize the project and verify that it works correctly inside the container.
9. **Git & GitHub** — Maintain meaningful commits and publish the completed project.

The emphasis is on **understanding the reasoning behind every implementation decision**, not simply making the code work.

---

Thanks for stopping by! ⭐

Feel free to explore the projects and follow the repository as it grows.

> Built with ❤️ through continuous learning, experimentation, and thoughtful software engineering.

**#BackendEngineering #NodeJS #JavaScript #SoftwareEngineering #DataStructures #Docker**
