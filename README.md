# Zolo (zolo)

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

Zolo is one of Canada's largest national residential real estate marketplaces and a licensed brokerage, operating as Zolo Ventures Ltd. with provincial brokerage subsidiaries — Zolo Realty (Ontario), (Alberta), (British Columbia), (Saskatchewan), (Manitoba) and (Quebec) Inc. — plus Zolo Mortgages Ltd. and Zolo Mortgages (Alberta) Ltd., all owned by Questrade Financial Group Inc. Founded in 2012 as a digital-first brokerage and headquartered at 1900-5700 Yonge Street in Toronto, Zolo reports over 10 million monthly visitors, 750+ active REALTORS®, and $1.5B+ in annual transaction volume across British Columbia, Alberta, Saskatchewan and Ontario. It sits in the Canadian challenger layer alongside HouseSigma, Wahi and Properly, below CREA — the single national cooperative that operates REALTOR.ca and the Data Distribution Facility (DDF) that syndicates member boards' listings — competing on listing speed, sold-price visibility and home-value tooling over data the boards and CREA control. Its API posture is closed. There is no developer portal, no API program page, no partner or data-licensing page, and no machine-readable contract of any kind. The subdomains api., developer., developers., docs., data. and partners.zolo.ca do not resolve in DNS, and every conventional contract path on www.zolo.ca is answered by a Cloudflare bot challenge (HTTP 403, `cf-mitigated: challenge`) rather than a specification. Zolo's own robots.txt declares a new-listings RSS syndication feed at `/rss_new_listings.php` and a CREA terms-acceptance route at `/crea_accept.php`, and Section 23 of its Terms of Use is a Virtual Office Website (VOW) clause requiring registration, a bona fide interest in buying or selling, personal non-commercial use only, and an express prohibition on "scraping" (including "screen scraping" and "database scraping"), data mining, redistribution or sublicensing — enforceable directly by CREA, TRREB, ITSO, REBGV, Pillar9 and OREB. Access is licensed, not open. RESO is absent: Zolo is not among the nineteen Canadian organizations RESO lists as members, and no Web API or Data Dictionary certification, OData `$metadata` document, or Universal Property Identifier (UPI) usage was found. No open, unlicensed dataset is published.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/zolo/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/zolo/refs/heads/main/apis.yml)

## Tags

- Real Estate
- Canada
- Property Listings
- MLS
- IDX
- Valuation
- AVM
- PropTech
- Rentals
- Mortgage
- Conveyancing

## Timestamps

- **Created:** 2026-07-26
- **Modified:** 2026-07-26

## APIs

No public, documented APIs. Zolo publishes no developer portal, no API program, and no machine-readable contract of any kind. The two machine-readable surfaces that exist — the `/rss_new_listings.php` syndication feed declared in `robots.txt` and the `/gallery_map_json.php` route that `robots.txt` disallows to all crawlers — carry no documentation, terms, versioning or key issuance, and the Terms of Use expressly forbid programmatic collection of the data behind them. They are implementation and SEO details, not developer products, and are therefore not listed here.

## RESO Posture

**Not RESO-certified. No RESO reference found.**

RESO's own [Canadian Membership](https://www.reso.org/canadian-membership/) page lists nineteen Canadian member organizations — CREA, Centris, Clientime, Falcon Technologies Corporation, Listed, Local Logic, Multi List Platform LP, MPAC, Origin Confirmed Ltd, Phoenix Software, Planitar, PropTexx, Prospects Software, the REALTORS® Association of Edmonton, the Real Estate Board of Greater Vancouver, the Saskatchewan REALTORS® Association, Templates 4 Business, the Victoria Real Estate Board and the Winnipeg Regional Real Estate Board — and Zolo is not among them. The [RESO certified organizations directory](https://www.reso.org/certificates/) contains no Canadian entries at all. No RESO Web API certification, no Data Dictionary certification or version, no OData `$metadata` document, and no Universal Property Identifier (UPI) usage was observed. This is the expected Canadian answer: RESO certification is a US industry mandate driven by NAR, while Canadian residential listings flow through CREA's national Data Distribution Facility (DDF) and individual board MLS® Systems — a route Zolo's own `robots.txt` records in the `/crea_accept.php` terms-acceptance path it disallows.

## Access Gate

**`none-published`.** For a developer there is nothing to sign up for, apply to, or join, because nothing is on offer — no portal, no API program, no partner page, no data-licensing page, no application form, no API terms, no keys.

Beneath the absent developer surface the data itself is licensed, and the licence is explicit. Section 23 of Zolo's [Terms of Use](https://www.zolo.ca/legal-terms) is a **Virtual Office Website (VOW)** clause. A user must register an account, warrant "a bona fide interest in the purchase, sale, or lease of real estate of the type being offered through Zolo", and use the data only for personal non-commercial purposes. It states verbatim: *"You will not, directly or indirectly, display, post, disseminate, distribute, publish, broadcast, transfer, sell or sublicense any data obtained through the VOW to another individual or entity. The prohibited uses expressly include 'scraping' (including 'screen scraping' and 'database scraping'), 'data mining' or any other activity intended to collect, store, re-organize, summarize or manipulate the data."* The user also expressly authorizes the Real Estate Boards to inspect their account information to enforce compliance. The named proprietors are CREA (owner of the REALTOR® and MLS® marks), the Toronto Regional Real Estate Board (TRREB), Information Technology Systems Ontario (ITSO), the Real Estate Board of Greater Vancouver (REBGV), Alberta One Realty Listing Services Inc. (Pillar9) and the Ottawa Real Estate Board (OREB).

Upstream, Zolo receives the data as a licensed brokerage with board/MLS membership through its provincial Zolo Realty subsidiaries — a corporate membership posture, not a developer onboarding path. A third party wanting this data must become a member brokerage or go to CREA's DDF instead.

## Open Data

**None.** No open, unlicensed, publicly callable dataset. The sitemaps declared in `robots.txt` are crawl indexes of HTML pages, and the `rss_new_listings.php` feed carries MLS® numbers on every item — board-licensed listing data with no terms, documentation or versioning attached. Canada has no counterpart to HM Land Registry Price Paid or Ordnance Survey open data; provincial land registration is largely privatised, with Teranet operating Ontario's registry under long concession, so even the public record is a commercial product here.

## Auth Model

**None published.** No API key programme, no OAuth 2.0 or OpenID Connect developer flow, no SAML member portal. `/.well-known/openid-configuration` returns HTTP 403 behind the Cloudflare challenge, and the Internet Archive shows every `/.well-known/` probe against zolo.ca resolving only as a 301 apex redirect — no discovery document has ever been served. Human authentication is ordinary session-based account sign-in, layered with the board-mandated VOW registration and the CREA terms-acceptance step at `/crea_accept.php`. Machine access is not authenticated so much as actively blocked: the Cloudflare edge answers non-browser clients with HTTP 403 and `cf-mitigated: challenge`, even with browser-identical headers.

## Webhooks, Events, SDKs, Postman

None found — the absence is itself the finding. No webhook or event documentation, no published SDK, no CLI, no Postman workspace or collection. No Zolo GitHub organization could be verified: [github.com/zolo](https://github.com/zolo) is a different company whose declared blog is zolo.io, and `github.com/zolocanada` is an empty organization with zero public repositories and no metadata, so neither is claimed here. Zolo does ship iOS and Android apps (governed by Section 24 of the Terms of Use), but their backend is undocumented and no contract is published for it.

## Artifacts

Enrichment round 2026-07-26. Every path on `www.zolo.ca` answers automated clients with a Cloudflare challenge, so several artifacts were recovered verbatim from Internet Archive snapshots and the provenance is recorded in each file.

- [`well-known/zolo-well-known.yml`](well-known/zolo-well-known.yml) — full STEP 0b contract-discovery log. All `/.well-known/*` and all OpenAPI/Swagger/GraphQL probes 403. Certificate Transparency (certspotter) confirms no `api.`, `developer.`, `docs.`, `data.` or `partners.` host has ever been certificated — only marketing, blog, training and four non-production environments (`sit`, `stg1`, `stg2`, `uat`). Negative result, so **no `WellKnown` pointer is wired**.
- [`well-known/zolo-robots.txt`](well-known/zolo-robots.txt) — verbatim `robots.txt` (Internet Archive, 2025-11-13). Declares six sitemaps plus the new-listings RSS feed, disallows `/gallery_map_json.php`, `/crea_accept.php` and `/_terms_modal.php`, and blocks YandexBot, Baiduspider, trovitBot and Sogou — but **names no AI crawler at all**.
- [`conventions/zolo-conventions.yml`](conventions/zolo-conventions.yml) — data-access conventions: the public RSS 2.0 feed (3,899 items observed), the XML sitemap family, the schema.org block, the undocumented map-JSON endpoint, the mobile backend, and the VOW licence model. No idempotency, pagination, versioning or error contract exists to record.
- [`conformance/zolo-conformance.yml`](conformance/zolo-conformance.yml) — conforms to robots.txt, sitemaps.org, RSS 2.0, schema.org and the CREA/board IDX-VOW display rules; does not conform to OpenAPI, GraphQL, AsyncAPI, MCP, OAuth 2.0, OIDC, RFC 9457, RFC 9116, RFC 8615, RFC 9727, llms.txt, OData, or any RESO certification. No compliance programme published, so **no `Compliance` pointer is wired**.
- [`json-ld/zolo-organization.jsonld`](json-ld/zolo-organization.jsonld) — the site-wide schema.org block, verbatim. `WebSite` + `Corporation`, self-reporting founding year 2012, the three founders, and the authoritative `sameAs` social list (the social pointers in `apis.yml` come from here, not from guesswork). No `RealEstateListing` markup anywhere — the listing content is exactly what the VOW licence forecloses.
- [`json-schema/zolo-map-listing.schema.json`](json-schema/zolo-map-listing.schema.json) — the observed shape of `/gallery_map_json.php`, derived from an archived response. 24 all-string fields including `lat`/`lng`, `board`, `agent_name` and the IDX display flags `show_idx`, `show_basic`, `disp_addr`. Descriptive research only: that endpoint is robots-disallowed and covered by the anti-scraping clause.
- [`packages/zolo-packages.yml`](packages/zolo-packages.yml) — npm, PyPI, RubyGems, Packagist, NuGet, crates.io and GitHub all searched; **no first-party client library exists**, so no `SDKs` pointer is wired. Records the two verified first-party mobile apps (`com.ols.zolo` on both stores) as the evidence of a private backend.
- [`security/zolo-domain-security.yml`](security/zolo-domain-security.yml) — probed: TLS 1.3, HSTS `max-age=31536000`, SPF and DMARC `p=reject`, CAA present, **no DNSSEC**. No security.txt, no disclosure policy, no bug bounty and no trust centre were found, so no `Security`, `VulnerabilityDisclosure` or `TrustCenter` artifact was written.
- [`llms/zolo-llms.txt`](llms/zolo-llms.txt) — generated (Zolo publishes none), telling an agent plainly that there is nothing to sign up for and pointing it at CREA's DDF or a member board feed instead.

## Common Properties

- [Website](https://www.zolo.ca/)
- [Blog](https://www.zolo.ca/blog)
- [Blog RSS](https://www.zolo.ca/blog/feed/)
- [New listings RSS feed](https://www.zolo.ca/rss_new_listings.php)
- [Sitemap index](https://www.zolo.ca/site_map_index_https.php)
- [Contact / Support](https://www.zolo.ca/contact_us.php)
- [Careers](https://www.zolo.ca/careers)
- [Terms of Service](https://www.zolo.ca/legal-terms)
- [Privacy Policy](https://www.zolo.ca/legal-privacy)
- [Privacy & Security Centre](https://www.zolo.ca/legal)
- [iOS app](https://apps.apple.com/ca/app/zolo-real-estate-apartments/id898656833) — [Android app](https://play.google.com/store/apps/details?id=com.ols.zolo)
- [LinkedIn](https://www.linkedin.com/company/zolocanada) · [Facebook](https://www.facebook.com/zolocanada) · [X](https://www.twitter.com/zolocanada) · [Instagram](https://www.instagram.com/zolocanada) · [YouTube](https://www.youtube.com/c/ZoloCanada) · [Pinterest](https://www.pinterest.com/zolocanada)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
