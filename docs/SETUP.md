# CRM RevOps Workflow Setup

## Components

1. **HubSpot Source** - Configure webhook events
2. **Zapier Middleware** - Transform payloads
3. **Code Nodes** - Custom JavaScript logic
4. **Database** - Store formatted data

## Webhook Configuration

1. Go to HubSpot Settings → Webhooks
2. Create new webhook for contacts/deals
3. Map to Zapier trigger
4. Test payload format

## Payload Transformation

Use JavaScript Code Nodes to:
- Extract nested fields
- Format timestamps
- Validate email addresses
- Calculate derived fields
