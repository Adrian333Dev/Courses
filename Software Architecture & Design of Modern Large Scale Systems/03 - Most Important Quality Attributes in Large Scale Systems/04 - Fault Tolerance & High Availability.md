# Fault Tolerance & High Availability

## Understanding Fault Tolerance

- **Definition:** Fault tolerance is the ability of a system to remain operational and available to users despite failures in one or more of its components.
- **Goal:** To achieve high availability by ensuring the system can handle failures without significant downtime or performance degradation.

## Sources of Failures

1. **Human Error:** Mistakes made during configuration, deployment, or maintenance.
2. **Software Errors:** Crashes due to bugs, memory leaks, or long garbage collections.
3. **Hardware Failures:** Breakdown of servers, routers, or storage devices due to wear and tear, power outages, or network issues.

## Tactics for Achieving Fault Tolerance

1. **Failure Prevention:**

   - **Replication and Redundancy:** Eliminate single points of failure by replicating critical components (e.g., running multiple instances of a service or database).
   - **Active-Active vs. Active-Passive:** Choose between spreading the load across all replicas (active-active) or having a primary replica with passive backups (active-passive).

2. **Failure Detection and Isolation:**

   - **Monitoring:** Use a monitoring system to detect failures through health checks, heartbeats, or monitoring error rates and response times.
   - **Isolation:** Once a failure is detected, isolate the faulty component to prevent it from affecting the rest of the system.

3. **Recovery:**
   - **Restarting:** Attempt to restart failed components to restore functionality.
   - **Rollback:** Revert to a previous stable version of the software or database state if a new update causes issues.

## Key Takeaways

- Fault tolerance is essential for maintaining high availability in large-scale systems.
- It involves a combination of preventive measures, effective detection and isolation of failures, and strategies for quick recovery.
- Achieving fault tolerance requires careful planning and implementation of redundancy, monitoring, and recovery mechanisms.

---

In this lecture, fault tolerance was discussed as a critical aspect of achieving high availability in large-scale systems, emphasizing the importance of replication, monitoring, and recovery strategies to handle various sources of failures.
