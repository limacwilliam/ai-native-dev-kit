# Runbook

| Symptom | Verify | Action |
|---|---|---|
| No reminders sent | Scheduler heartbeat and queue depth | Pause rollout, restore scheduler, replay only idempotent jobs |
| Duplicates reported | Idempotency key and audit events | Stop worker, investigate key generation, contact affected recipients |
