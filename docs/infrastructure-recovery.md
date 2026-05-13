# Infrastructure Recovery Plan

## Core Principles

- Every service must be recoverable independently
- Docker containers are disposable
- Persistent data must survive container recreation
- Backups are mandatory
- Infrastructure must remain migration-ready

---

# Critical Services

## PostgreSQL
Purpose:
Primary source of truth

Backup Required:
YES

Recovery Priority:
HIGH

---

## n8n
Purpose:
Workflow orchestration

Backup Required:
YES

Recovery Priority:
HIGH

---

## Portainer
Purpose:
Container management

Backup Required:
OPTIONAL

Recovery Priority:
LOW

---

# Backup Rules

1. Database backups mandatory
2. Workflow exports mandatory
3. Environment configs versioned
4. Recovery process documented
5. No critical secrets committed to GitHub

---

# Failure Recovery Philosophy

Containers may fail.
Data must survive.