# System Quality Attributes Requirements

## Understanding Quality Attributes

- **Definition:** Quality attributes, or nonfunctional requirements, describe how well the system performs certain dimensions, rather than what the system does.
- **Motivation:** Systems are often redesigned not due to functional deficiencies, but because they lack the necessary quality attributes like performance, scalability, or maintainability.

## Key Considerations for Quality Attributes

1. **Measurability and Testability:**

   - Quality attributes must be measurable and testable to objectively determine if the system meets the requirements.
   - Example: Specifying that a user interface should respond "quickly" is subjective; instead, define a measurable response time like 100 milliseconds.

2. **Trade-offs and Prioritization:**

   - No single architecture can provide all quality attributes optimally.
   - Software architects need to make trade-offs, prioritizing some quality attributes over others based on business requirements.
   - Example: Balancing speed and security in a login process may require compromising on one attribute to enhance the other.

3. **Feasibility:**
   - Ensure that the quality attributes are technically feasible and realistic.
   - Consider factors like network latency, bandwidth limitations, and physical constraints when setting quality attribute goals.
   - Example: A requirement for 100% system availability is unrealistic, as it implies the system can never fail or undergo maintenance.

## Examples of Quality Attributes

- **Performance:** The system responds to user actions within 100 milliseconds.
- **Availability:** The online store is available to users at least 99.9% of the time.
- **Deployability:** The development team can deploy a new version of the online store at least twice a week.

## Summary

- Quality attributes are crucial for determining the architecture of a system and ensuring it meets the needs of all stakeholders.
- They require careful definition, prioritization, and feasibility assessment to avoid costly redesigns and ensure the system's success.

---

In this lecture, the significance of quality attributes in system design was emphasized, along with the importance of making them measurable, prioritizing them based on business needs, and ensuring their feasibility.

## References

- [Previous Lecture](./02%20-%20Feature%20Requirements%20-%20Step%20by%20Step%20Process.md)
- [Next Lecture](./04%20-%20System%20Constraints%20in%20Software%20Architecture.md)
