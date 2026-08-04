# Respond.io (respond)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
