# Marcus by Goldman Sachs (marcus)

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

Marcus by Goldman Sachs is the U.S. consumer banking brand of The Goldman Sachs Group, launched in 2016 to offer no-fee high-yield Online Savings Accounts and Certificates of Deposit (CDs) directly to retail customers online. Deposits are held at Goldman Sachs Bank USA, a New York State-chartered bank and member of the Federal Reserve System, insured by the FDIC.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/marcus/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/marcus/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Marcus by Goldman Sachs operates **no public first-party consumer developer API** and runs **no self-serve developer portal** for its retail banking products. The separate Goldman Sachs Developer platform ([developer.gs.com](https://developer.gs.com/)) serves institutional Transaction Banking and Marquee offerings — not Marcus consumer banking. That platform was not reachable from a non-browser client during this review (HTTP 000, bot-blocked).

Consumer-permissioned Marcus account data (balances, transactions, account/holder details) is reachable only through third-party open-finance aggregators — **not** a documented Marcus API:

- **Plaid** (confirmed): supports Assets, Auth, Balance, Transactions, and Investments for Marcus, across Depository, Loan, Investment, and Other account types (US only).
- **Flinks** and **MX** are also referenced as aggregator paths to Marcus data.

As a U.S. bank, Goldman Sachs Bank USA is subject to the emerging **CFPB Section 1033** personal financial data rights framework, but no first-party **FDX**-conformant Marcus developer interface is publicly documented as of this record. This is the honest, non-fabricated reality for most U.S. consumer banks: data access via aggregators only.

## Tags

- Financial Services
- Banking
- United States
- Consumer Banking
- Neobank
- Digital Banking
- Savings
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Marcus Consumer Data Access (Aggregator-Only)

Marcus does not publish a first-party consumer developer API. Consumer-permissioned account data is available only through third-party open-finance aggregators. This is an honest data-access pointer, not a Marcus-operated API.

- **Human URL:** [https://plaid.com/institutions/marcus-by-goldman-sachs/](https://plaid.com/institutions/marcus-by-goldman-sachs/)

#### Tags

- Data Aggregation
- Open Finance
- Consumer Data

#### Properties

- [Documentation](https://plaid.com/institutions/marcus-by-goldman-sachs/)

## Common Properties

- [Website](https://www.marcus.com/us/en)
- [LinkedIn](https://www.linkedin.com/company/goldman-sachs)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
