# Scalability

## Understanding Scalability

- **Definition:** Scalability is the measure of a system's ability to handle a growing amount of work by adding more resources in a cost-effective way.
- **Motivation:** System load can vary due to seasonal traffic, daily patterns, or business growth, necessitating scalable design to maintain performance.

## Three Dimensions of Scalability

1. **Vertical Scalability (Scaling Up):**

   - Adding or upgrading resources on a single computer (e.g., faster CPU, more memory).
   - Pros: Simple, no code changes needed.
   - Cons: Limited by hardware capabilities, doesn't provide high availability or fault tolerance.

2. **Horizontal Scalability (Scaling Out):**

   - Adding more instances of resources across multiple machines.
   - Pros: Virtually unlimited scalability, can provide high availability and fault tolerance.
   - Cons: May require significant code changes, increased complexity and coordination overhead.

3. **Team or Organizational Scalability:**
   - Increasing productivity by adding more engineers to the team.
   - Challenges: Productivity can decrease beyond a certain team size due to coordination overhead, merge conflicts, and increased learning curve.
   - Solutions: Modularize codebase, separate concerns into services for independent development and deployment.

## Key Takeaways

- Scalability is crucial for systems experiencing variable or growing traffic.
- Systems can be scaled vertically (upgrading hardware), horizontally (adding more instances), and organizationally (improving team productivity).
- Each scalability dimension has its advantages and challenges, and they can be combined to achieve optimal performance and productivity.

---

In this lecture, scalability was discussed as a vital quality attribute for large-scale systems, highlighting the importance of designing for vertical, horizontal, and team scalability to accommodate varying and increasing system loads.

## References

- [Previous Lecture](./01%20-%20Performance.md)
- [Next Lecture](./03%20-%20Availability%20-%20Introduction%20&%20Measurement.md)
