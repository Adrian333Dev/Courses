# SLA, SLO, SLI

## Understanding SLA, SLO, and SLI

- **Service Level Agreement (SLA):** A legal contract between the service provider and the users, outlining the quality of service promised, including availability, performance, and response times. It also specifies penalties for failing to meet these promises.
- **Service Level Objective (SLO):** Individual goals set for the system's performance and availability. SLOs are the targets that the service aims to meet, such as 99.9% uptime or response times under 100 milliseconds.
- **Service Level Indicator (SLI):** Quantitative measures used to evaluate the system's performance against the SLOs. SLIs are the actual metrics collected, such as the percentage of successful requests or average response times.

## Considerations for Setting SLOs

1. **Focus on User-Centric Metrics:** Define SLOs around metrics that matter most to users, and find appropriate SLIs to track them.
2. **Limit the Number of SLOs:** Having too many SLOs can make it difficult to prioritize and meet all of them. Focus on a few key objectives.
3. **Set Realistic Goals with Error Budgets:** Commit to achievable SLOs that allow some room for error. This helps in managing costs and avoiding penalties.
4. **Prepare a Recovery Plan:** Have a plan in place to address situations where SLIs indicate that SLOs are not being met. This plan should include alerts, failovers, restarts, and rollbacks.

## Key Takeaways

- SLAs, SLOs, and SLIs are crucial for defining, measuring, and managing the quality of service in large-scale systems.
- Setting appropriate SLOs and monitoring SLIs helps ensure that the system meets user expectations and contractual obligations outlined in the SLA.
- It's important to balance ambition with realism when setting SLOs and to have contingency plans in place for handling potential breaches of these objectives.

---

In this lecture, the concepts of Service Level Agreement (SLA), Service Level Objective (SLO), and Service Level Indicator (SLI) were explored, highlighting their roles in aggregating and measuring the promises made to users regarding system quality attributes. Key considerations for setting SLOs were also discussed, emphasizing the importance of user-centric metrics, realistic goals, and preparedness for recovery.

## References

- [Previous Lecture](./04%20-%20Fault%20Tolerance%20&%20High%20Availability.md)
- [Next Lecture](./06%20-%20Real%20World%20SLA%20Examples%20from%20the%20Industry.md)
