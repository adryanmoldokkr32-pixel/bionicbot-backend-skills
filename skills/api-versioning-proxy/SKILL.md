---
name: api-versioning-proxy
description: Manage multiple API versions without breaking user experience.
---

# API Versioning Proxy

This skill ensures that as the system evolves, old versions of the app continue to work perfectly.

## Instructions
1. Implement Header-based or URL-based versioning.
2. Use a reverse proxy (NGINX/Traefik) to route traffic to specific versions.
3. Automate 'Sunset' warnings for legacy API endpoints.
4. Ensure backward compatibility in database schemas.

## Examples
- "Route all V1 requests to our legacy Node.js service while V2 handles new traffic."