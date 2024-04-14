# Relational Databases & ACID Transactions

## Introduction to Relational Databases

- **Overview:** Relational databases organize data into tables where each row represents a record with predefined columns, facilitating complex queries and data relationships using SQL (Structured Query Language).

## Characteristics of Relational Databases

- **Data Organization:** Data is systematically stored in tables, defined by a schema that specifies each column's name, type, and constraints.
- **Primary Keys:** Unique identifiers (either single or composite keys) distinguish each row in a table.
- **Schema Rigidity:** The structure of data is predetermined and modifications to the schema can be complex and disruptive.

## Advantages of Relational Databases

- **Data Integrity:** Through relationships defined between tables, relational databases efficiently manage data integrity and reduce redundancy.
- **Query Power:** SQL provides robust tools for data manipulation and retrieval, supporting complex analytical queries and transactions.
- **ACID Transactions:** Ensures data reliability through Atomicity, Consistency, Isolation, and Durability:
  - **Atomicity:** Guarantees that all operations within a transaction are completed successfully or not at all.
  - **Consistency:** Ensures that database transactions only bring the database from one valid state to another, maintaining database invariants.
  - **Isolation:** Protects transaction from interference from other concurrent transactions.
  - **Durability:** Ensures that the result of a committed transaction persists, even in the case of a system failure.

## Disadvantages of Relational Databases

- **Schema Inflexibility:** Requires upfront schema definition which can be inflexible and challenging to modify as application requirements evolve.
- **Scalability Challenges:** While relational databases can handle significant loads, they traditionally scale vertically rather than horizontally, which can be less cost-effective and more complex in distributed environments.
- **Complexity and Cost:** The robust features of relational databases, such as supporting ACID properties and complex joins, can lead to higher operational complexity and costs.

## Use Cases for Relational Databases

- **Complex Transactions:** Ideal for applications requiring complex transactions or where business logic needs strong data integrity and consistency.
- **Data Analysis:** Suitable for scenarios where intricate queries are necessary for analytics and reporting.
- **Regulated Industries:** Frequently used in environments where transaction integrity is critical, such as finance and healthcare.

## Choosing Relational Databases

- **Criteria for Selection:** Should be chosen based on the need for complex transactions, the importance of data integrity, and when the application logic closely aligns with a relational data model.
- **Considerations:** It’s crucial to evaluate the application needs against the potential scalability challenges and the overhead of maintaining a rigid schema.

## Conclusion

Relational databases remain a fundamental choice for storing structured data that requires stringent data integrity and complex querying capabilities. They are particularly valuable in scenarios where relationships between data entities are complex and ACID compliance is required. However, the trade-offs in terms of schema flexibility and scalability must be carefully considered, especially when designing systems intended to scale at a global level. The next lectures will explore alternative database technologies that might better suit different scenarios, especially those requiring more flexibility or horizontal scaling.
