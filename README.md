# Federal Communications Commission (federal-communications-commission)

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

The Federal Communications Commission (FCC) regulates interstate and international communications by radio, television, wire, satellite, and cable in the United States. The FCC exposes public APIs including the Electronic Comment Filing System (ECFS) and the FCC Open Data portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Communications
- Federal Government
- Open Data

## Timestamps

- **Created:** 2024-12-03
- **Modified:** 2026-05-19

## APIs

### FCC ECFS API

The FCC Electronic Comment Filing System (ECFS) public API provides programmatic access to filings, proceedings, and submissions made to the Federal Communications Commission.

- **Human URL:** [https://www.fcc.gov/ecfs/](https://www.fcc.gov/ecfs/)
- **Base URL:** `https://publicapi.fcc.gov/ecfs`

#### Tags

- Communications
- Filings
- Proceedings

#### Properties

- [Documentation](https://www.fcc.gov/reports-research/developers)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/openapi/ecfs.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/rules/ecfs-rules.yml)
- [Postman Collection](collections/ecfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ecfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/opendata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/opendata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### FCC Open Data API

The FCC Open Data Portal exposes datasets via the Socrata Open Data API (SODA), including the Pirate Radio Broadcasting Database, broadband deployment data, and consumer complaint summaries.

- **Human URL:** [https://opendata.fcc.gov/](https://opendata.fcc.gov/)
- **Base URL:** `https://opendata.fcc.gov`

#### Tags

- Communications
- Open Data
- Broadband

#### Properties

- [Documentation](https://opendata.fcc.gov/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/openapi/opendata.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Rules](https://raw.githubusercontent.com/api-evangelist/federal-communications-commission/refs/heads/main/rules/opendata-rules.yml)
- [Postman Collection](collections/ecfs.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ecfs.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/opendata.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/opendata.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/fcc)
- [LinkedIn](https://www.linkedin.com/company/federal-communications-commission)
- [Website](https://www.fcc.gov/)
- [Documentation](https://www.fcc.gov/reports-research/developers)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
