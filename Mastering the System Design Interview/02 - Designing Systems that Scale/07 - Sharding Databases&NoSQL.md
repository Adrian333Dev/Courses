# 07 - Sharding Databases / NoSQL

1. **Sharding Databases**:

   - Sharding involves partitioning a database horizontally into multiple "shards" to improve scalability and redundancy.
   - Each shard contains a subset of the data and can have one or more backups for resiliency.
   - A router routes requests from clients to the appropriate shard based on a hash function or another method.
   - Sharding allows for scalability and resiliency, but combining data across shards can be complex and inefficient.

2. **NoSQL Databases**:

   - NoSQL databases are non-relational and designed for scalability above all else.
   - MongoDB, for example, uses a sharded architecture with replica sets for each shard.
   - Each shard has a primary server and multiple secondary servers, which can automatically elect a new primary if the current one fails.
   - MongoDB uses a config server to store information about shard distribution and primary servers.
   - Cassandra uses a ring system where any node can act as the primary interface, eliminating single points of failure but sacrificing some consistency.

3. **Denormalization**:

   - Denormalization involves duplicating data across tables or documents to improve query performance by reducing the need for joins.
   - While denormalization can improve performance, it can also lead to data redundancy and inconsistency.
   - The choice between normalized and denormalized data structures depends on the specific requirements and trade-offs of the application.

4. **Trade-offs**:
   - Sharding and denormalization can improve performance and scalability but require careful design and consideration of trade-offs.
   - NoSQL databases often use SQL as their primary API but may not support complex joins efficiently.
   - Designing around key-value lookups can improve scalability and performance in NoSQL databases.
