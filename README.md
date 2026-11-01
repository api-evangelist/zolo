# Zolo

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

Zolo is one of Canada's largest national residential real estate marketplaces and a licensed brokerage, operating as Zolo Ventures Ltd. with provincial brokerage subsidiaries — Zolo Realty (Ontario), (Alberta), (British Columbia), (Saskatchewan), (Manitoba) and (Quebec) Inc. — plus Zolo Mortgages Ltd. and Zolo Mortgages (Alberta) Ltd., all owned by Questrade Financial Group Inc. Founded in 2012 as a digital-first brokerage and headquartered at 1900-5700 Yonge Street in Toronto, Zolo reports over 10 million monthly visitors, 750+ active REALTORS®, and $1.5B+ in annual transaction volume across British Columbia, Alberta, Saskatchewan and Ontario. It sits in the Canadian challenger layer alongside HouseSigma, Wahi and Properly, below CREA — the single national cooperative that operates REALTOR.ca and the Data Distribution Facility (DDF) that syndicates member boards' listings — competing on listing speed, sold-price visibility and home-value tooling over data the boards and CREA control. Its API posture is closed. There is no developer portal, no API program page, no partner or data-licensing page, and no machine-readable API contract of any kind — no OpenAPI, GraphQL, AsyncAPI or MCP surface. The subdomains api., developer., developers., docs., data. and partners.zolo.ca do not resolve in DNS and have never appeared in Certificate Transparency, and every conventional contract path on www.zolo.ca is answered by a Cloudflare bot challenge (HTTP 403, cf-mitigated: challenge) rather than a specification. What Zolo does publish is syndication, not integration: an unauthenticated RSS 2.0 new-listings feed at /rss_new_listings.php, a family of sitemaps.org XML documents, and a site-wide schema.org JSON-LD block carrying organization identity only. Behind the edge it operates an undocumented JSON endpoint at /gallery_map_json.php and two first-party mobile apps (com.ols.zolo) on a private backend. Zolo's own robots.txt declares that RSS feed as a sitemap and a CREA terms-acceptance route at /crea_accept.php, and Section 23 of its Terms of Use is a Virtual Office Website (VOW) clause requiring registration, a bona fide interest in buying or selling, personal non-commercial use only, and an express prohibition on "scraping" (including "screen scraping" and "database scraping"), data mining, redistribution or sublicensing — enforceable directly by CREA, TRREB, ITSO, REBGV, Pillar9 and OREB. Access is licensed, not open. RESO is absent: Zolo is not among the nineteen Canadian organizations RESO lists as members, and no Web API or Data Dictionary certification, OData $metadata document, or Universal Property Identifier (UPI) usage was found. No open, unlicensed dataset is published.

**Areas:** Real Estate · Canada · Property Listings · MLS · IDX · Valuation · AVM · PropTech · Rentals · Mortgage · Conveyancing

## Zolo on APIs.io

Everything profiled for Zolo is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/zolo/](https://apis.io/providers/zolo/)** — or go straight to one of the APIs or properties below.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### JSON Schema (1)

The data models the API reads and writes.

- [Zolo map-gallery listing](https://apis.io/schemas/zolo/zolo-map-listing.schema/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Zolo Organization Context](https://apis.io/jsonld/zolo/zolo-organization/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Zolo Domain Security](https://apis.io/security/zolo/zolo-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.zolo.ca/)
- [Support](https://www.zolo.ca/contact_us.php)
- [Blog](https://www.zolo.ca/blog)
- [Terms of service](https://www.zolo.ca/legal-terms)
- [Privacy policy](https://www.zolo.ca/legal-privacy)

## API Evangelist rating

**Kin Score 13.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 48.2 |
| Contract quality | 6.7 |
| Contract governance | 4.5 |
| Operational transparency | 0.0 |
| Developer ergonomics | 7.1 |
| Access clarity | 21.1 |

**Agent readiness 0.0** — human-only

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 18.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/zolo/](https://apis.io/providers/zolo/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Zolo: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/zolo/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
