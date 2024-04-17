# Availability - Introduction & Measurement

## Importance of High Availability

- **User Impact:** Unavailability can lead to user frustration and loss of trust.
- **Business Impact:** Downtime can result in lost revenue and customers potentially switching to competitors.

## Defining and Measuring Availability

- **Availability:** The fraction of time or probability that a service is operationally functional and accessible to users.
- **Uptime:** The time when the system is operational and accessible.
- **Downtime:** The time when the system is unavailable or non-operational.
- **Measurement:** Availability is typically measured as a percentage, calculated as `(Uptime) / (Uptime + Downtime) * 100%`.

## Alternative Measurement: MTBF and MTTR

- **Mean Time Between Failures (MTBF):** The average time the system is operational before a failure occurs.
- **Mean Time To Recovery (MTTR):** The average time it takes to detect and recover from a failure.
- **Availability Formula:** `Availability = MTBF / (MTBF + MTTR)`.

## Understanding High Availability

- **Industry Standards:** High availability is generally considered to be 99.9% availability or higher.
- **Nomenclature:** Availability is often referred to by the number of nines (e.g., "three nines" for 99.9% availability).
- **Impact of Recovery Time:** Minimizing the recovery time (MTTR) is crucial for achieving high availability.

## Key Takeaways

- High availability is crucial for both user satisfaction and business continuity.
- Availability can be measured using uptime/downtime percentages or statistically using MTBF and MTTR.
- Achieving high availability requires careful planning and implementation of strategies to minimize downtime and quickly recover from failures.

---

In this lecture, the significance of high availability in large-scale systems was emphasized, with a focus on its impact on users and businesses. The concepts of availability, uptime, downtime, MTBF, and MTTR were introduced as measures to define and assess the availability of a system. The industry standards for high availability were also discussed, highlighting the importance of striving for "three nines" or above.

## References

- [Previous Lecture](./02%20-Scalability.md)
- [Next Lecture](./04%20-%20Fault%20Tolerance%20&%20High%20Availability.md)
