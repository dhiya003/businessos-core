# PostgreSQL Recovery Procedure

## Backup Location

~/BusinessOS/backups/postgres

## Create Backup

~/BusinessOS/backups/scripts/backup-postgres.sh

## Restore Procedure

docker exec -i businessos-postgres psql -U businessos businessos < backup.sql

## Recovery Principles

- Always verify backup integrity
- Never overwrite active DB without backup
- Test recovery periodically
- Database remains source of truth