# Event Driven Patterns

Event-driven architecture is increasingly common in Power Platform integrations.

## What Is Event Driven Architecture

Systems publish events when something happens.

Other systems react to those events.

This avoids tight coupling.

## Example Event Flow

1. record created in Dataverse
2. event published
3. integration service receives event
4. downstream systems process independently

## Benefits

Event-driven approaches provide:

- scalability
- resilience
- system independence
- easier evolution of integrations

## Common Technologies

Typical components include:

- Azure Service Bus
- event processing services
- integration microservices
- logging and monitoring systems

## Design Advice

Design events carefully:

- define clear event types
- include meaningful identifiers
- keep payloads manageable
- design consumers to tolerate duplicates