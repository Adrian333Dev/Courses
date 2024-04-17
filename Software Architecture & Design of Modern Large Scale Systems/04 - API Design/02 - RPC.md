# RPC (Remote Procedure Call)

## Introduction to RPC

- **Remote Procedure Calls (RPC):** A style of API that allows client applications to execute routines on a remote server as if they were local functions. This method provides "local transparency," making remote method invocations appear similar to local method calls.

## How RPC Works

- **Interface Description Language:** Used to define the API and data types, facilitating communication between remote clients and servers.
- **Stub Generation:** A code generation tool is used to create server and client stubs based on the interface description. These stubs handle the implementation details of the remote procedure invocation.
- **Data Transfer Objects (DTOs):** Auto-generated classes or structs that encapsulate the data used in API methods, also known as DTOs.

## Runtime Process

1. **Serialization:** Client stub serializes the data (marshalling) and sends it to the remote server.
2. **Deserialization:** Server stub receives the data, deserializes it, and invokes the corresponding method on the server.
3. **Response Handling:** After the server processes the request, it serializes the response and sends it back to the client, where it is deserialized by the client stub.

## Benefits of RPC

- **Simplicity for Developers:** Developers can call remote methods as if they were local, simplifying the integration process.
- **Language Agnosticity:** Supports multiple programming languages, allowing different systems to interact seamlessly.
- **Abstraction:** Abstracts the complexities of network communication, focusing only on method functionalities.

## Drawbacks of RPC

- **Performance Issues:** Remote calls are generally slower and less reliable than local calls, which can lead to unexpected bottlenecks.
- **Error Handling Complexity:** Network issues can result in errors that are difficult for clients to interpret correctly, such as whether an operation should be retried.

## Best Practices for RPC Design

- **Asynchronous Methods:** For long-running operations, provide asynchronous method variants to prevent blocking in client applications.
- **Idempotent Operations:** Design operations to be idempotent where possible, reducing the risk of adverse effects if a method is called multiple times.

## When to Use RPC

- **Backend Communication:** Ideal for interactions between backend systems where operations are action-focused rather than data-centric.
- **Internal System Integration:** Useful within an organization to connect different internal systems seamlessly.
- **Limited Frontend Use:** Less common for frontend applications directly interacting with users.

## Summary

In this lecture, RPC was explored as a foundational API style suited for enabling remote method invocations that feel like local calls. The discussion covered how RPCs work, their advantages, and the challenges they present. Best practices were highlighted to mitigate potential issues such as performance lags and unreliable network communications, ensuring effective use of RPC in appropriate scenarios.

## References

- [Previous Lecture](./01%20-%20Introduction%20to%20API%20Design%20for%20Software%20Architects.md)
- [Next Lecture](./03%20-%20Popular%20RPC%20Frameworks%20and%20Technologies.md)
