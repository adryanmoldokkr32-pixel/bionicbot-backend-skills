---
name: webhook-integrator
description: Build and manage systems that respond to real-time events from other apps.
---

# Webhook Integrator

This skill focuses on creating endpoints that receive and process data sent from third-party services (e.g., Stripe, GitHub, Shopify).

## Instructions

1. Design the receiving endpoint (POST route).
2. Implement signature verification to ensure requests are authentic.
3. Handle the payload data and trigger internal workflows.
4. Manage asynchronous processing for heavy tasks (using queues).
5. Log webhook events for debugging and reliability.

## Examples

- "Integrate a Stripe webhook to activate a user's subscription after payment."
- "Create a GitHub webhook receiver that triggers a build on every push."