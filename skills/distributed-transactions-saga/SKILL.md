---
name: distributed-transactions-saga
description: Manage complex transactions across multiple microservices.
---

# Distributed Transactions (Saga)

This skill focuses on ensuring data consistency when a single user action affects multiple independent services.

## Instructions
1. Implement the 'Saga' pattern (Choreography or Orchestration).
2. Define compensating transactions for every step (to undo changes on failure).
3. Ensure eventual consistency across distributed databases.
4. Monitor transaction state and latency.

## Examples
- "Implement a Saga for a payment flow involving Billing and Inventory services."