# Respond.io (respond)

Respond.io is an AI-powered customer-conversation management platform that unifies omnichannel messaging - WhatsApp, Messenger, Instagram, Telegram, SMS, email, and website chat - into a single inbox. Its REST Developer API lets businesses manage contacts, send and read messages across channels, manage conversations, post comments, apply tags and custom fields, and subscribe to webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/respond/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/respond/refs/heads/main/apis.yml)

## Tags

- Messaging
- Omnichannel
- Customer Conversations
- WhatsApp
- AI

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Respond.io Contacts API

Access, create, update, merge, list, and delete contacts. Contacts are addressed by an identifier of the form id:{id}, email:{email}, or phone:{phone}, with support for tags, custom fields, lifecycle, and channel listing.

- **Human URL:** [https://developers.respond.io/docs/api/c6e1aa937640e-contact](https://developers.respond.io/docs/api/c6e1aa937640e-contact)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Contacts
- CRM
- Identity

#### Properties

- [Documentation](https://developers.respond.io/)
- [API Reference](https://developers.respond.io/docs/api/c6e1aa937640e-contact)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/respond.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/respond.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Respond.io Messages API

Send messages to a contact across any connected channel (text, attachment, quick replies, WhatsApp template, email) and read individual messages or list a contact's message history. Routes to the last interacted channel when channelId is omitted.

- **Human URL:** [https://developers.respond.io/docs/api/a748f5bfb1bb5-send-a-message](https://developers.respond.io/docs/api/a748f5bfb1bb5-send-a-message)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Messages
- Send
- Omnichannel

#### Properties

- [Documentation](https://developers.respond.io/)
- [API Reference](https://developers.respond.io/docs/api/42fc125b57906-messaging)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/respond.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/respond.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Respond.io Conversations API

Open and close conversations for a contact, set conversation status, and assign or unassign users (human agents or AI agents) to the conversation.

- **Human URL:** [https://developers.respond.io/docs/api/fd927d6437cf5-conversation](https://developers.respond.io/docs/api/fd927d6437cf5-conversation)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Conversations
- Inbox
- Assignment

#### Properties

- [Documentation](https://developers.respond.io/)
- [API Reference](https://developers.respond.io/docs/api/fd927d6437cf5-conversation)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/respond.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/respond.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Respond.io Comments API

Create internal comments on a contact's conversation for team collaboration, with support for mentioning users. Comments are not sent to the contact.

- **Human URL:** [https://developers.respond.io/](https://developers.respond.io/)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Comments
- Internal Notes
- Collaboration

#### Properties

- [Documentation](https://developers.respond.io/)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/respond.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/respond.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Respond.io Tags and Custom Fields API

Manage workspace tags (create, update, delete) and add or remove them on contacts, plus list and create custom fields used to store structured contact metadata.

- **Human URL:** [https://developers.respond.io/](https://developers.respond.io/)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Tags
- Custom Fields
- Metadata

#### Properties

- [Documentation](https://developers.respond.io/)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/respond.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/respond.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Respond.io Webhooks API

Subscribe to platform events (new message, message status, new contact, conversation opened/closed) delivered to your server as structured JSON payloads over HTTPS.

- **Human URL:** [https://developers.respond.io/](https://developers.respond.io/)
- **Base URL:** `https://api.respond.io/v2`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://developers.respond.io/)
- [OpenAPI](openapi/respond-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Review](review.yml)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/respond-io)
- [Website](https://respond.io/)
- [Documentation](https://developers.respond.io/)
- [Plans](plans/respond-plans-pricing.yml)
- [Rate Limits](rate-limits/respond-rate-limits.yml)
- [Fin Ops](finops/respond-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
