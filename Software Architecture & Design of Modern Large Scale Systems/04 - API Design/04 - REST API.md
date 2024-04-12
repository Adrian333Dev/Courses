# REST API

## Introduction to REST API

- **REST (Representational State Transfer):** Developed by Roy Fielding, REST is an architectural style for designing networked applications. It is not a standard or protocol but a set of guidelines that emphasizes scalability, statelessness, and the efficient use of network resources.

## Core Concepts of REST API

- **Resource-Based:** Resources are the key abstraction of information in REST. Each resource is identified by URIs and is manipulated using a standard set of methods (HTTP methods in web-based REST APIs).
- **Stateless:** Each request from client to server must contain all the information needed to understand and complete the request. The server does not store session information about clients.
- **Cacheable:** Responses must define themselves as cacheable or not, to prevent clients from reusing stale or inappropriate data.
- **Uniform Interface:** REST APIs should have a uniform interface that simplifies and decouples the architecture, which enables each part to evolve independently.

## Designing RESTful APIs

1. **Identify Resources:** Determine what types of data or services the API will expose (e.g., users, movies, reviews).
2. **Define Resource URIs:** Create intuitive and hierarchical URIs for each resource and sub-resource (e.g., /movies, /movies/{id}/reviews).
3. **Select Representation Formats:** Decide how resources will be represented, typically using formats like JSON or XML.
4. **Assign HTTP Methods:** Map CRUD (Create, Read, Update, Delete) operations to HTTP methods:
   - **GET** for retrieving resources.
   - **POST** for creating resources.
   - **PUT** for updating resources.
   - **DELETE** for deleting resources.
5. **State Transitions Through Hypermedia:** Use hypermedia links within resource representations to manage state transitions and make the API self-descriptive.

## Benefits of REST API

- **Scalability:** Stateless operations allow the server to quickly free resources, supporting more clients.
- **Simplicity:** Standard HTTP methods reduce the complexity of actions that can be performed on resources.
- **Independence:** The separation of client and server allows each to evolve independently.

## Best Practices for REST API Design

- **Use Nouns for Resource Names:** Resources should be named using nouns (e.g., "users") and not verbs (e.g., "getUser").
- **Plural Nouns for Collections:** Use plural nouns for collections (e.g., "movies") and singular nouns for individual items (e.g., "movie").
- **Consistent Naming Conventions:** Maintain consistency in naming conventions and resource hierarchies to avoid confusion.
- **Versioning:** Version APIs to manage changes gracefully and support older clients while encouraging them to upgrade.
- **Security:** Implement authentication and authorization techniques to secure access to resources.

## Challenges and Considerations

- **Over-fetching and Under-fetching:** Design endpoints to provide exactly what's needed by the client to avoid fetching unnecessary data or making multiple requests for data.
- **Error Handling:** Clearly communicate errors through standard HTTP status codes and provide messages that help clients handle errors effectively.

---

In this lecture, REST was presented as a powerful API design style ideal for web services, emphasizing how resources are managed and accessed through a set of well-defined operations. The lecture also outlined how to design and implement a RESTful API by following best practices and addressing common challenges.
