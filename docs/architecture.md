# BusinessOS Architecture

## Core Principles

- Local-first
- Docker-first
- Migration-ready
- Multi-repo architecture
- Shared core + isolated modules
- Workflow-centric orchestration initially
- Human approval for critical actions
- Revenue before infrastructure scaling
- Modular activation-based business systems

## Current Stack

### Infrastructure
- Docker Desktop
- Portainer

### Data Layer
- PostgreSQL

### Automation Layer
- n8n

### Development
- VS Code
- GitHub
- Git

## Governance Rules

1. Database is source of truth
2. n8n orchestrates only
3. Business logic remains modular
4. Avoid premature complexity
5. Reusable systems preferred
6. Human approval for financial actions
7. Every service containerized where appropriate