---
name: environment-var-protector
description: Securely manage and protect sensitive secrets and API keys.
---

# Environment Var Protector

This skill focuses on the 'secrets' hygiene of a project, ensuring no keys are leaked and all are stored correctly.

## Instructions

1. Identify sensitive keys (DB passwords, API tokens).
2. Move secrets from code to `.env` files or Secret Managers (AWS Secrets Manager, HashiCorp Vault).
3. Ensure `.env` is always in `.gitignore`.
4. Implement different secrets for Development, Staging, and Production.
5. Audit code history for previously accidentally committed secrets.

## Examples

- "Audit this repo for any hardcoded API keys."
- "Configure GitHub Secrets for a secure CI/CD pipeline."