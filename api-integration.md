# API Integration

Power Platform frequently integrates with external REST APIs.

## Common Scenarios

- retrieving external data
- sending updates to external systems
- orchestrating workflows across platforms
- exposing services to portals

## Integration Options

- Power Automate connectors
- Azure Functions acting as API gateways
- direct API calls from integration services
- middleware platforms

## Good API Practices

- validate inputs and outputs
- design for retries
- implement authentication securely
- log requests and failures
- version APIs carefully

## Avoid Tight Coupling

Do not tightly couple portal UI or plugins directly to external APIs if reliability is uncertain.

Use intermediate services where possible.