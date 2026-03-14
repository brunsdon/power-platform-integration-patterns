# Dataverse Integration

Dataverse can be integrated with external systems using several approaches.

## Common Integration Options

- Dataverse Web API
- Power Automate
- plugins triggering external services
- Azure Functions
- messaging platforms such as Service Bus

## When to Use Web API

Web API is suitable for:

- CRUD operations
- synchronous integrations
- external system access
- administrative operations
- automation scripts

## When to Use Power Automate

Power Automate is often useful for:

- event-driven automation
- simple integration scenarios
- Microsoft ecosystem workflows
- low-volume event processing

## When to Use Azure Integration

Azure-based integration services are useful when:

- processing large volumes
- integrating multiple systems
- building resilient message-based workflows
- implementing event-driven architecture

## Practical Advice

Think carefully about:

- transaction boundaries
- retry behaviour
- data ownership
- error handling
- monitoring

Avoid building integration logic that depends on fragile synchronous workflows.