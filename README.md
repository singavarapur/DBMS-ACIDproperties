A simple approach to view and analyse about ACID properties in databases. 
1. Atomicity
Definition: Atomicity ensures that a transaction is treated as a single, indivisible unit of work. This means that either all operations within the transaction are completed successfully, or none of them are applied at all.
2. Consistency
Definition: Consistency ensures that a transaction brings the database from one valid state to another valid state, maintaining all predefined rules, constraints, and relationships. After a transaction is completed, the database must be in a consistent state.
3. Isolation
Definition: Isolation ensures that transactions are executed in isolation from one another. This means that the operations of one transaction should not be visible to other transactions until the transaction is completed. This prevents transactions from interfering with each other.
4. Durability
Definition: Durability guarantees that once a transaction has been committed, it will remain so, even in the event of a system failure. This means that the results of a transaction are permanently recorded in the database.

This can be viewed by seeing changes in postgres dbms. 
