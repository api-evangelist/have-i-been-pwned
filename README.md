# Have I Been Pwned (have-i-been-pwned)

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
