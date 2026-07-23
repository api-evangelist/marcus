# Marcus by Goldman Sachs (marcus)

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
