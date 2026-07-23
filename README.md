# UBS Bank USA (ubs-bank-usa)

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
