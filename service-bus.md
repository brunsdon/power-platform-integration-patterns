# Service Bus

Azure Service Bus enables reliable asynchronous communication between systems.

## Why Messaging Is Useful

Messaging decouples systems so that:

- producers do not depend on consumers
- workloads can scale independently
- temporary failures do not break workflows

## Typical Pattern

1. event occurs in Dataverse
2. message is published
3. one or more consumers process the message

This allows multiple downstream systems to respond independently.

## Common Messaging Components

- queues
- topics
- subscriptions
- dead letter queues

## Benefits

Using messaging provides:

- resilience
- scalability
- separation of concerns
- improved fault tolerance

## Practical Advice

Design messages carefully:

- include meaningful identifiers
- include timestamps
- avoid unnecessary payload size
- design consumers to handle retries