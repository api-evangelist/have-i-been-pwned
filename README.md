# Have I Been Pwned (have-i-been-pwned)

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

Have I Been Pwned (HIBP) is a free service operated by Troy Hunt that lets individuals and organizations check whether their email addresses, phone numbers, passwords, or domains have appeared in known data breaches, pastes, or stealer logs. The service aggregates billions of compromised records and exposes both free and paid endpoints, including the k-anonymity Pwned Passwords API. The v3 REST API at haveibeenpwned.com requires an hibp-api-key header for breach, paste, domain, and stealer log endpoints and is offered across Core, Pro, and High RPM subscription tiers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/have-i-been-pwned/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/have-i-been-pwned/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Security
- Data Breaches
- Pwned Passwords
- Identity
- Threat Intelligence
- Credential Stuffing

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### Have I Been Pwned API v3

REST API for searching breached accounts, pastes, breach metadata, domain breach data, and stealer log entries. Authentication requires an hibp-api-key header (32-character key) along with a descriptive user-agent header. Most endpoints require a paid subscription; rate limits range from 600 to 100,000 requests per minute depending on tier.

- **Human URL:** [https://haveibeenpwned.com/API/v3](https://haveibeenpwned.com/API/v3)
- **Base URL:** `https://haveibeenpwned.com/api/v3`

#### Tags

- Breaches
- Pastes
- Stealer Logs
- Domain Search
- Account Search

#### Properties

- [Documentation](https://haveibeenpwned.com/API/v3)
- [Authentication](https://haveibeenpwned.com/API/Key)
- [Pricing](https://haveibeenpwned.com/API/Key)
- [Postman Collection](collections/have-i-been-pwned.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/have-i-been-pwned.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Pwned Passwords API

Free, unauthenticated, k-anonymity-based API to check whether a password hash appears in the 800+ million record Pwned Passwords dataset. Clients submit the first five characters of a SHA-1 hash and receive a list of matching suffixes with counts. No rate limit and no attribution required.

- **Human URL:** [https://haveibeenpwned.com/API/v3#PwnedPasswords](https://haveibeenpwned.com/API/v3#PwnedPasswords)
- **Base URL:** `https://api.pwnedpasswords.com`

#### Tags

- Passwords
- K-Anonymity
- SHA-1
- Credential Stuffing

#### Properties

- [Documentation](https://haveibeenpwned.com/API/v3#PwnedPasswords)
- [Project](https://haveibeenpwned.com/Passwords)
- [Postman Collection](collections/have-i-been-pwned.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/have-i-been-pwned.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/HaveIBeenPwned)
- [LinkedIn](https://www.linkedin.com/company/haveibeenpwned)
- [Website](https://haveibeenpwned.com)
- [Documentation](https://haveibeenpwned.com/API/v3)
- [Pricing](https://haveibeenpwned.com/API/Key)
- [Sign Up](https://haveibeenpwned.com/API/Key)
- [F A Q](https://haveibeenpwned.com/FAQs)
- [Blog](https://www.troyhunt.com)
- [Twitter](https://twitter.com/haveibeenpwned)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
