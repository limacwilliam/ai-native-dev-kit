# Technical specification

A scheduled worker selects due confirmed appointments, writes an idempotency record, then calls a notification adapter. The adapter interface allows replacement without changing scheduling logic. Failures are retried with bounded exponential backoff.
