---
name: caching-strategist-redis
description: Use Redis or Memcached to speed up applications and reduce load.
---

# Caching Strategist (Redis)

This skill focuses on reducing response times by storing frequently accessed data in high-speed memory.

## Instructions

1. Identify expensive operations (API calls, complex DB queries).
2. Implement a 'Cache Aside' or 'Write Through' strategy.
3. Set appropriate Expiration (TTL) times for different data types.
4. Manage cache invalidation when data changes.
5. Use Redis for rate limiting or distributed session management.

## Examples

- "Cache the results of a heavy dashboard query for 5 minutes."
- "Use Redis to limit API requests to 100 per minute per user."