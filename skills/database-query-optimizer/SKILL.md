---
name: database-query-optimizer
description: Analyze and optimize slow database queries for speed.
---

# Database Query Optimizer

This skill focuses on identifying bottlenecks in database performance and rewriting queries for maximum efficiency.

## Instructions

1. Identify slow queries using EXPLAIN ANALYZE or slow query logs.
2. Suggest missing indexes for WHERE and JOIN clauses.
3. Rewrite complex subqueries into joins or CTEs when beneficial.
4. Optimize schema types to reduce disk I/O.
5. Recommend caching strategies for repetitive read-heavy queries.

## Examples

- "Optimize this slow SQL query that joins 5 large tables."
- "Suggest indexes for a 'users' table with 10 million rows."