# Webhooks

Webhooks allow Dataverse to notify external systems when events occur.

## Common Uses

- notifying external services of record changes
- triggering downstream processes
- integrating with integration middleware

## Typical Flow

1. record created or updated
2. webhook triggered
3. external service receives payload
4. service processes event

## Important Considerations

- webhooks are synchronous
- failures may affect transaction behaviour
- payload size and complexity should be controlled
- receiving services must respond quickly

## When To Use

Webhooks are suitable for:

- simple integration triggers
- notifying integration middleware
- lightweight event handling

For complex integration logic, queue-based patterns are often safer.