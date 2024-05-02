# Failover Strategies

## Physical Server Provisioning

- Servers physically exist in data centers.
- Companies may have their own data centers or use cloud services.
- Cloud services like AWS (EC2) allow renting virtual machines.
- Cloud services handle maintenance, but you need a strategy for server failure.

## Cloud Services

- Cloud services provide redundancy options (e.g., different regions, availability zones).
- Serverless services (e.g., AWS Lambda) abstract server management entirely.
- Billing is based on usage, providing cost control.

## Scaling Databases

- **Cold Standby**: Periodic backups to some storage for a standby server. In case of failure, the backup is restored to a new server.
  - High downtime and potential data loss.
  - Suitable for internal tools but not production systems.
- **Warm Standby**: Constant replication to a standby server. In case of failure, the standby server can be promoted to the primary server.
  - Low downtime and minimal data loss.
  - Increased load on the standby server.
- **Hot Standby**: Simultaneous writing to multiple database instances. In case of failure, the standby server can be promoted to the primary server.
  - Enables horizontal scaling for reads and writes.
  - More complex but offers better scalability.

## Conclusion

- Cloud services offer scalability and redundancy options.
- Different failover strategies (cold, warm, hot standby) offer varying levels of downtime, data loss, and complexity.
- Horizontal scaling is achievable through hot standby strategies.
