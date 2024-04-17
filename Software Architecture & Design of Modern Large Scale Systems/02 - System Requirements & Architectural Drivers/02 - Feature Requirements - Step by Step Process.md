# Feature Requirements - Step by Step Process

## Capturing Functional Requirements: A Step-by-Step Method

1. **Identify Actors/Users:** Ensure all relevant users and actors in the system are identified to capture their use cases.
2. **Describe Use Cases:** Outline all possible scenarios in which an actor interacts with the system.
3. **Expand Use Cases into User Flows:** For each use case, detail the flow of events or interactions between the actor and the system, noting the actions and data involved.

## Use Cases and User Flows

- **Use Case:** A scenario in which the system is used to achieve a user's goal.
- **User Flow:** A detailed step-by-step or graphical representation of a use case, showing interactions between the actor and the system.

## Example: Hitchhiking Service

- **Actors:** Driver and Rider.
- **Use Cases:** Registration of a new rider/driver, logging in, successful/unsuccessful match, completion of a ride.
- **User Flow (Sequence Diagram):**
  - Driver logs in and notifies the system of their route.
  - Rider logs in and requests a ride.
  - System matches the rider with a driver.
  - Driver picks up the rider, and the ride begins.
  - Upon completion, the system charges the rider and credits the driver's account.

## Sequence Diagrams

- **Description:** A type of diagram representing interactions between actors and objects over time.
- **Components:** Vertical lines represent entities, arrows represent communications, and broken lines represent responses.
- **Usage:** Frequently used to represent interactions in a system, although UML is not strictly followed in the industry.

## Benefits and Future Steps

- **API Identification:** The user flow can help identify the future API of the system, as each interaction can be seen as an API call.
- **Next Lectures:** Designing APIs and further exploration of system design aspects.

---

In this lecture, a formal method for capturing and documenting functional requirements through use cases and user flows was introduced, with an example of a hitchhiking service to illustrate the process. Sequence diagrams were presented as a tool for visualizing interactions in the system.

## References

- [Previous Lecture](./01%20-%20Introduction%20to%20System%20Design%20&%20Architectural%20Drivers.md)
- [Next Lecture](./03%20-%20System%20Quality%20Attributes%20Requirements.md)
