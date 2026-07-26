# Zolo (zolo)

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

## Common Properties

- [Website](https://www.zolo.ca/)
- [Blog](https://www.zolo.ca/blog)
- [Blog RSS](https://www.zolo.ca/blog/feed/)
- [Terms of Service](https://www.zolo.ca/legal-terms)
- [Privacy Policy](https://www.zolo.ca/legal-privacy)
- [Privacy & Security Centre](https://www.zolo.ca/legal)
- [LinkedIn](https://www.linkedin.com/company/zolocanada)

## Maintainers

- **Kin Lane** — kin@apievangelist.com
