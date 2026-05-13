# Workflow Execution Schema

## Core Identity
- execution_id
- workflow_name
- workflow_category

## Timing
- started_at
- completed_at
- duration_ms

## Status
- execution_status
- retry_count
- failure_reason

## Context
- affected_module
- triggered_by
- environment

## Metadata
- records_processed
- ai_used
- notification_sent

## Debugging
- error_stack
- workflow_version