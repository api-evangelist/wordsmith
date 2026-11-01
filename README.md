# Wordsmith

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

Wordsmith is an Edinburgh-based legal AI platform built for in-house legal teams, marketed as a Slack-native legal copilot that lets non-legal staff self-serve compliant answers, templates, and contract reviews directly in the tools they already use. The product line includes the Wordsmith Assistant (a chat surface that answers routine legal questions, summarises documents, and runs contract review against organisation-specific Playbooks), Templates (parameterised DOCX/Markdown document generation with placeholder fields and fallback clause logic), Playbooks (codified review rules used to flag non-standard terms in NDAs, MSAs, DPAs and similar agreements and to propose pre-approved compromise positions), and a growing set of channel integrations centred on Slack, Microsoft Teams, Gmail, Outlook, Microsoft Word, Google Docs/Drive, SharePoint, OneDrive, Notion, Confluence, Dropbox, Salesforce, HubSpot, Attio, Ironclad, Juro, Asana, Monday.com, Jira, Linear, Granola, Google Sheets, and Excel, plus programmatic reach via an MCP server, Zapier, and n8n. Wordsmith exposes a public REST API documented at wordsmithai.mintlify.app with Bearer-token authentication and resources for Assistants (ask a question with optional file attachments, poll question status, list assistants available to the account), Files (presigned upload URLs for documents), Playbooks (list accessible review playbooks), Templates (list accessible templates), User (get-me for the authenticated user and organisation), plus signed Webhooks for asynchronous notifications. The company was founded in October 2023 by Ross McNairn (CEO, formerly Head of Product at Skyscanner and CPTO at TravelPerk), Robbie Falkenthal (COO), and Volodymyr Giginyak (CTO), is headquartered in Edinburgh with offices in London and New York, raised a $25M Series A from Index Ventures in June 2025 at a reported $100M valuation, and counts Trustpilot, Skyscanner, AutoTrader, Deliveroo, BT, Trip.com, Coursera, Canva, The Financial Times, Remote.com, Multiverse, and Docplanner among its customers. Pricing is published as an Individual plan at $450 per user per month and a custom Enterprise plan, with a 30-minute book-a-demo flow as the primary onboarding path. WORDSMITH is a registered trade mark of Wordsmith Law LLP and is used under licence by Wordsmith AI.

**Areas:** Legal · Legal Tech · Legal AI · In-House Legal · General Counsel · Contract Review · Contract Lifecycle Management · Document Generation · Playbooks · Templates · AI Assistant · AI Agents

## Wordsmith on APIs.io

Everything profiled for Wordsmith is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/wordsmith/](https://apis.io/providers/wordsmith/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [Wordsmith Platform API](https://apis.io/apis/wordsmith/platform-api/) — Public REST API for the Wordsmith legal AI platform. Lets developers ask questions of Wordsmith Assistants with optional file attachments, poll question…
- [Wordsmith MCP Server](https://apis.io/apis/wordsmith/mcp-server/) — Model Context Protocol server that exposes Wordsmith Assistants, Playbooks, and Templates to MCP-aware clients (Claude, agent frameworks, IDEs) so legal…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Wordsmith Domain Security](https://apis.io/security/wordsmith/wordsmith-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.wordsmith.ai)
- [Documentation](https://wordsmithai.mintlify.app/)
- [Getting started](https://wordsmithai.mintlify.app/quickstart)
- [API reference](https://wordsmithai.mintlify.app/api-reference/user/get-me)
- [Pricing](https://www.wordsmith.ai/pricing)
- [Blog](https://www.wordsmith.ai/blog)
- [Security](https://www.wordsmith.ai/security)
- [Trust centre](https://app.vanta.com/wordsmith.ai/trust/ze3ctf4wjcl4713io5yps)
- [Terms of service](https://www.wordsmith.ai/terms-of-service)
- [Privacy policy](https://www.wordsmith.ai/privacy-policy)

## API Evangelist rating

**Kin Score 15.1** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 13.2 |
| Developer ergonomics | 42.9 |
| Access clarity | 0.0 |

**Agent readiness 9.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | unknown |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/wordsmith/](https://apis.io/providers/wordsmith/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Wordsmith: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/wordsmith/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
