# CRM RevOps Architecture

## Data Flow

```
HubSpot Contact Updated
    ↓
Webhook Triggered
    ↓
Zapier Catches Event
    ↓
Code Node Transforms
    ↓
Database Updated
    ↓
Notification Sent
```

## Key Concepts

- **Webhook Events** - Real-time HubSpot updates
- **Payload** - Event data structure
- **Code Node** - Zapier JavaScript execution
- **Field Mapping** - Source to destination alignment
- **Idempotency** - Prevent duplicate processing
