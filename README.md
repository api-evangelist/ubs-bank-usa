# UBS Bank USA (ubs-bank-usa)

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

UBS Bank USA (BUSA) is a Utah state-chartered industrial bank and FDIC-insured depository institution headquartered in Salt Lake City, Utah, established in 2003 and reporting roughly $122 billion in total assets. It is the primary US banking vehicle of UBS Wealth Management Americas, providing FDIC-insured deposit sweep programs, securities-based lending, mortgages, and credit cards to the high-net-worth and ultra-high-net-worth advisory clients of parent UBS Group AG. It is supervised by the FDIC, the Utah Department of Financial Institutions, and the CFPB.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ubs-bank-usa/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ubs-bank-usa/refs/heads/main/apis.yml)

## Open-Finance / API Posture

UBS Bank USA exposes **no first-party public developer API surface of its own**. As an advisor-led wealth bank rather than a fintech or Banking-as-a-Service provider, its products are delivered through UBS Financial Advisors, not self-serve APIs.

- **First-party developer portal:** None for the US entity. The only live UBS developer portal, [developer.ubs.com](https://developer.ubs.com) (HTTP 200), belongs to **UBS Switzerland** and serves Swiss/EU products — key4 mortgages, QR-bill, PSD2, TWINT, bLink, and KeyPort (EBICS) — not UBS Bank USA.
- **Downloadable OpenAPI/Swagger:** None found (US or Swiss portal did not surface publicly downloadable specs during this harvest).
- **FDX (Financial Data Exchange):** No documented UBS Bank USA participation found. UBS is not among the listed Akoya owner banks, and no FDX-conformant BUSA data-access API is published.
- **CFPB Section 1033:** No published BUSA-specific 1033 / data-rights posture located. BUSA is CFPB-supervised, which would bring it in scope of the Personal Financial Data Rights rule as it phases in.
- **Aggregator access:** US consumer-permissioned data access, where available, is mediated by third-party aggregators (Plaid / MX / Finicity / Akoya) rather than a documented first-party BUSA API.

## Tags

- Financial Services
- Banking
- United States
- Wealth Management
- Industrial Bank
- Securities-Based Lending
- Private Banking

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public, documented first-party APIs for UBS Bank USA were found during this bootstrap harvest. This is an honest identity-only record.

## Common Properties

- [Website](https://www.ubs.com)
- [Developer Portal (UBS Switzerland group portal — not BUSA)](https://developer.ubs.com)
- [Documentation](https://developer.ubs.com/get-started)
- [Support](https://developer.ubs.com/support)
- [Blog](https://developer.ubs.com/blog)
- [LinkedIn](https://www.linkedin.com/company/ubs)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
