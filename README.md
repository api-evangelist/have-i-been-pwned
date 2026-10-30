# Have I Been Pwned

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
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

**Areas:** Security · Data Breaches · Pwned Passwords · Identity · Threat Intelligence · Credential Stuffing

## Have I Been Pwned on APIs.io

Everything profiled for Have I Been Pwned is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/have-i-been-pwned/](https://apis.io/providers/have-i-been-pwned/)** — or go straight to one of the APIs or properties below.

### APIs (21)

- [Have I Been Pwned API v3](https://apis.io/apis/have-i-been-pwned/api-v3/) — REST API for searching breached accounts, pastes, breach metadata, domain breach data, and stealer log entries. Authentication requires an hibp-api-key…
- [Pwned Passwords API](https://apis.io/apis/have-i-been-pwned/pwned-passwords/) — Free, unauthenticated, k-anonymity-based API to check whether a password hash appears in the 800+ million record Pwned Passwords dataset. Clients submit the…
- [Have I Been Pwned Breach API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-breach-api/) — The Breach API from Have I Been Pwned — 1 operation(s) for breach.
- [Have I Been Pwned Breachedaccount API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-breachedaccount-api/) — The Breachedaccount API from Have I Been Pwned — 2 operation(s) for breachedaccount.
- [Have I Been Pwned Breacheddomain API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-breacheddomain-api/) — The Breacheddomain API from Have I Been Pwned — 1 operation(s) for breacheddomain.
- [Have I Been Pwned Breaches API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-breaches-api/) — The Breaches API from Have I Been Pwned — 1 operation(s) for breaches.
- [Have I Been Pwned Domainverification API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-domainverification-api/) — The Domainverification API from Have I Been Pwned — 3 operation(s) for domainverification.
- [Have I Been Pwned Latestbreach API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-latestbreach-api/) — The Latestbreach API from Have I Been Pwned — 1 operation(s) for latestbreach.
- [Have I Been Pwned Pasteaccount API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-pasteaccount-api/) — The Pasteaccount API from Have I Been Pwned — 1 operation(s) for pasteaccount.
- [Have I Been Pwned Range API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-range-api/) — The Range API from Have I Been Pwned — 1 operation(s) for range.
- [Have I Been Pwned Stealerlogsbyemail API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-stealerlogsbyemail-api/) — The Stealerlogsbyemail API from Have I Been Pwned — 1 operation(s) for stealerlogsbyemail.
- [Have I Been Pwned Stealerlogsbyemaildomain API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-stealerlogsbyemaildomain-api/) — The Stealerlogsbyemaildomain API from Have I Been Pwned — 1 operation(s) for stealerlogsbyemaildomain.
- [Have I Been Pwned Stealerlogsbywebsitedomain API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-stealerlogsbywebsitedomain-api/) — The Stealerlogsbywebsitedomain API from Have I Been Pwned — 1 operation(s) for stealerlogsbywebsitedomain.
- [Have I Been Pwned Subscribeddomains API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-subscribeddomains-api/) — The Subscribeddomains API from Have I Been Pwned — 1 operation(s) for subscribeddomains.
- [Have I Been Pwned Subscription API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-subscription-api/) — The Subscription API from Have I Been Pwned — 1 operation(s) for subscription.
- [Have I Been Pwned Breached Accounts API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-breached-accounts-api/) — Lookup breaches affecting an email address.
- [Have I Been Pwned Data Classes API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-data-classes-api/) — Enumerate classes of data exposed across breaches.
- [Have I Been Pwned Domain Search API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-domain-search-api/) — Verify and search domains you control.
- [Have I Been Pwned Pastes API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-pastes-api/) — Lookup pastes referencing an email address.
- [Have I Been Pwned Range Search API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-range-search-api/) — K-anonymity range search for password hashes.
- [Have I Been Pwned Stealer Logs API](https://apis.io/apis/have-i-been-pwned/have-i-been-pwned-stealer-logs-api/) — Search infostealer malware corpora by email or domain.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Have I Been Pwned Agentic Access](https://apis.io/agentic-access/have-i-been-pwned/have-i-been-pwned-agentic-access/)

#### JSON Schema (6)

The data models the API reads and writes.

- [Breach](https://apis.io/schemas/have-i-been-pwned/hibp-breach/)
- [BreachedAccountRangeEntry](https://apis.io/schemas/have-i-been-pwned/hibp-breached-account-range-entry/)
- [Paste](https://apis.io/schemas/have-i-been-pwned/hibp-paste/)
- [SubscribedDomain](https://apis.io/schemas/have-i-been-pwned/hibp-subscribed-domain/)
- [SubscriptionStatus](https://apis.io/schemas/have-i-been-pwned/hibp-subscription-status/)
- [PwnedPasswordsRangeResult](https://apis.io/schemas/have-i-been-pwned/pwned-passwords-range-result/)

#### JSON Structure (3)

Data models expressed in JSON Structure.

- [Hibp Breach Structure](https://apis.io/json-structure/have-i-been-pwned/hibp-breach-structure/)
- [Hibp Paste Structure](https://apis.io/json-structure/have-i-been-pwned/hibp-paste-structure/)
- [Hibp Subscription Status Structure](https://apis.io/json-structure/have-i-been-pwned/hibp-subscription-status-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Have I Been Pwned Context](https://apis.io/jsonld/have-i-been-pwned/have-i-been-pwned-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [HaveIBeenPwned Vocabulary](https://apis.io/vocabularies/have-i-been-pwned/have-i-been-pwned-vocabulary/)

#### Examples (15)

Example requests and responses.

- [Hibp Generate Dns Token Example](https://apis.io/examples/have-i-been-pwned/hibp-generate-dns-token-example/)
- [Hibp Get Breach By Name Example](https://apis.io/examples/have-i-been-pwned/hibp-get-breach-by-name-example/)
- [Hibp Get Breached Domain Example](https://apis.io/examples/have-i-been-pwned/hibp-get-breached-domain-example/)
- [Hibp Get Breaches By Range Example](https://apis.io/examples/have-i-been-pwned/hibp-get-breaches-by-range-example/)
- [Hibp Get Breaches For Account Example](https://apis.io/examples/have-i-been-pwned/hibp-get-breaches-for-account-example/)
- [Hibp Get Latest Breach Example](https://apis.io/examples/have-i-been-pwned/hibp-get-latest-breach-example/)
- [Hibp Get Pastes For Account Example](https://apis.io/examples/have-i-been-pwned/hibp-get-pastes-for-account-example/)
- [Hibp Get Stealer Logs By Email Domain Example](https://apis.io/examples/have-i-been-pwned/hibp-get-stealer-logs-by-email-domain-example/)
- [Hibp Get Stealer Logs By Email Example](https://apis.io/examples/have-i-been-pwned/hibp-get-stealer-logs-by-email-example/)
- [Hibp Get Stealer Logs By Website Domain Example](https://apis.io/examples/have-i-been-pwned/hibp-get-stealer-logs-by-website-domain-example/)
- [Hibp Get Subscription Status Example](https://apis.io/examples/have-i-been-pwned/hibp-get-subscription-status-example/)
- [Hibp List Breaches Example](https://apis.io/examples/have-i-been-pwned/hibp-list-breaches-example/)
- [Hibp List Data Classes Example](https://apis.io/examples/have-i-been-pwned/hibp-list-data-classes-example/)
- [Hibp List Subscribed Domains Example](https://apis.io/examples/have-i-been-pwned/hibp-list-subscribed-domains-example/)
- [Pwned Passwords Search Range Example](https://apis.io/examples/have-i-been-pwned/pwned-passwords-search-range-example/)

#### Collections (31)

Postman and Open Collection request collections.

- [Have I Been Pwned API v3](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned/)
- [Have I Been Pwned API v3 Breach API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-breach-api/)
- [Have I Been Pwned API v3 Breached Accounts API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-breached-accounts-api/)
- [Have I Been Pwned API v3 Breach Breachedaccount API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-breachedaccount-api/)
- [Have I Been Pwned API v3 Breach Breacheddomain API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-breacheddomain-api/)
- [Have I Been Pwned API v3 Breach Breaches API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-breaches-api/)
- [Have I Been Pwned API v3 Breached Accounts Data Classes API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-data-classes-api/)
- [Have I Been Pwned API v3 Breach Dataclasses API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-dataclasses-api/)
- [Have I Been Pwned API v3 Breached Accounts Domain Search API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-domain-search-api/)
- [Have I Been Pwned API v3 Breach Domainverification API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-domainverification-api/)
- [Have I Been Pwned API v3 Breach Latestbreach API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-latestbreach-api/)
- [Have I Been Pwned API v3 Breach Pasteaccount API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-pasteaccount-api/)
- [Have I Been Pwned API v3 Breached Accounts Pastes API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-pastes-api/)
- [Have I Been Pwned API v3 Breach Range API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-range-api/)
- [Have I Been Pwned API v3 Breached Accounts Range Search API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-range-search-api/)
- [Have I Been Pwned API v3 Breached Accounts Stealer Logs API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-stealer-logs-api/)
- [Have I Been Pwned API v3 Breach Stealerlogsbyemail API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-stealerlogsbyemail-api/)
- [Have I Been Pwned API v3 Breach Stealerlogsbyemaildomain API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-stealerlogsbyemaildomain-api/)
- [Have I Been Pwned API v3 Breach Stealerlogsbywebsitedomain API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-stealerlogsbywebsitedomain-api/)
- [Have I Been Pwned API v3 Breach Subscribeddomains API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-subscribeddomains-api/)
- [Have I Been Pwned API v3 Breach Subscription API](https://apis.io/collections/have-i-been-pwned/open-have-i-been-pwned-subscription-api/)
- [Have I Been Pwned API v3](https://apis.io/collections/have-i-been-pwned/open-hibp/)
- [Pwned Passwords API](https://apis.io/collections/have-i-been-pwned/open-pwned-passwords/)
- [Have I Been Pwned API v3 Breached Accounts API](https://apis.io/collections/have-i-been-pwned/postman-have-i-been-pwned-breached-accounts-api/)
- [Have I Been Pwned API v3 Breached Accounts Breaches API](https://apis.io/collections/have-i-been-pwned/postman-have-i-been-pwned-breaches-api/)
- …and 6 more published on APIs.io

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Have I Been Pwned — jsonschema rules](https://apis.io/rules/have-i-been-pwned/have-i-been-pwned-jsonschema-spectral-rules/)
- [Have I Been Pwned — hibp rules](https://apis.io/rules/have-i-been-pwned/hibp-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Have I Been Pwned Authentication](https://apis.io/security/have-i-been-pwned/have-i-been-pwned-authentication/)
- [Have I Been Pwned Domain Security](https://apis.io/security/have-i-been-pwned/have-i-been-pwned-domain-security/)
- [Have I Been Pwned Vulnerability Disclosure](https://apis.io/security/have-i-been-pwned/have-i-been-pwned-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Have I Been Pwned Plans Pricing](https://apis.io/plans/have-i-been-pwned/have-i-been-pwned-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Have I Been Pwned Rate Limits](https://apis.io/rate-limits/have-i-been-pwned/have-i-been-pwned-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Have I Been Pwned Finops](https://apis.io/finops/have-i-been-pwned/have-i-been-pwned-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://haveibeenpwned.com)
- [Documentation](https://haveibeenpwned.com/API/v3)
- [Pricing](https://haveibeenpwned.com/API/Key)
- [Support](https://haveibeenpwned.com/Contact)
- [Blog](https://www.troyhunt.com)
- [Terms of service](https://haveibeenpwned.com/API/v3#License)
- [Privacy policy](https://haveibeenpwned.com/Privacy)
- [GitHub](https://github.com/HaveIBeenPwned)
- [Status](https://status.haveibeenpwned.com)

## API Evangelist rating

**Kin Score 47.3** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 56.3 |
| Contract governance | 27.3 |
| Operational transparency | 28.9 |
| Developer ergonomics | 34.5 |
| Access clarity | 52.6 |

**Agent readiness 31.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/have-i-been-pwned/](https://apis.io/providers/have-i-been-pwned/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Have I Been Pwned: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/have-i-been-pwned/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
