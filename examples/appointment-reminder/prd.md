# PRD: appointment reminder

## Problem

People occasionally miss appointments because they forget the scheduled time.

## Success

Send one reminder 24 hours before an appointment, with no duplicate sends.

## Acceptance criteria

- A reminder is sent only for confirmed appointments.
- Opted-out recipients receive nothing.
- Every send attempt is auditable without message content.
