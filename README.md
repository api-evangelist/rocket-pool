# Rocket Pool

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

Rocket Pool is a decentralized Ethereum liquid staking protocol that lets anyone participate in Ethereum proof-of-stake without running a full 32 ETH validator. Stakers deposit ETH and receive rETH, a rebasing-free yield-bearing liquid staking token that automatically accrues consensus and execution layer rewards and is freely composable across DeFi. On the supply side, permissionless node operators can run a Rocket Pool minipool with as little as 8 ETH (and a smaller RPL bond) — Rocket Pool pairs operator ETH with the rETH-backed deposit pool to fund full beacon-chain validators, and operators earn consensus rewards plus a commission from rETH users and RPL inflation rewards. The protocol is governed on-chain through the Protocol DAO (pDAO) and the Oracle DAO (oDAO) and is specified by Rocket Pool Improvement Proposals (RPIPs). The reference node software stack is the Smart Node (rocketpool CLI plus a Go daemon) distributed as Docker images, alongside Go and TypeScript/JavaScript libraries (rocketpool-go, rocketpool-js) for reading and writing protocol state directly against the Rocket Pool smart contracts on Ethereum mainnet. Rocket Pool has no centralized REST API, no hosted developer platform, no API keys, and no pricing — all participation is on-chain via Ethereum JSON-RPC and the protocol's deployed contracts.

**Areas:** Blockchain · Ethereum · Liquid Staking · Proof of Stake · DeFi · Smart Contracts · Node Operators · Validator · Reth · RPL · Minipool · Decentralized Finance

## Rocket Pool on APIs.io

Everything profiled for Rocket Pool is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rocket-pool/](https://apis.io/providers/rocket-pool/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Rocket Pool Protocol API (rocketpool-js)](https://apis.io/apis/rocket-pool/rocketpool-js-protocol-api/) — The rocketpool-js library is a TypeScript/JavaScript client for the Rocket Pool protocol's deployed smart contracts. It mirrors much of the Go library's…
- [Rocket Pool Auction API](https://apis.io/apis/rocket-pool/rocket-pool-auction-api/) — The Auction API from Rocket Pool — 3 operation(s) for auction.
- [Rocket Pool Deposit API](https://apis.io/apis/rocket-pool/rocket-pool-deposit-api/) — The Deposit API from Rocket Pool — 1 operation(s) for deposit.
- [Rocket Pool Megapool API](https://apis.io/apis/rocket-pool/rocket-pool-megapool-api/) — The Megapool API from Rocket Pool — 3 operation(s) for megapool.
- [Rocket Pool Minipool API](https://apis.io/apis/rocket-pool/rocket-pool-minipool-api/) — The Minipool API from Rocket Pool — 7 operation(s) for minipool.
- [Rocket Pool Network API](https://apis.io/apis/rocket-pool/rocket-pool-network-api/) — The Network API from Rocket Pool — 7 operation(s) for network.
- [Rocket Pool Node API](https://apis.io/apis/rocket-pool/rocket-pool-node-api/) — The Node API from Rocket Pool — 12 operation(s) for node.
- [Rocket Pool OracleDAO API](https://apis.io/apis/rocket-pool/rocket-pool-oracledao-api/) — The OracleDAO API from Rocket Pool — 2 operation(s) for oracledao.
- [Rocket Pool ProtocolDAO API](https://apis.io/apis/rocket-pool/rocket-pool-protocoldao-api/) — The ProtocolDAO API from Rocket Pool — 4 operation(s) for protocoldao.
- [Rocket Pool Queue API](https://apis.io/apis/rocket-pool/rocket-pool-queue-api/) — The Queue API from Rocket Pool — 2 operation(s) for queue.
- [Rocket Pool Rewards API](https://apis.io/apis/rocket-pool/rocket-pool-rewards-api/) — The Rewards API from Rocket Pool — 4 operation(s) for rewards.
- [Rocket Pool Service API](https://apis.io/apis/rocket-pool/rocket-pool-service-api/) — The Service API from Rocket Pool — 2 operation(s) for service.
- [Rocket Pool Settings API](https://apis.io/apis/rocket-pool/rocket-pool-settings-api/) — The Settings API from Rocket Pool — 1 operation(s) for settings.
- [Rocket Pool Tokens API](https://apis.io/apis/rocket-pool/rocket-pool-tokens-api/) — The Tokens API from Rocket Pool — 2 operation(s) for tokens.
- [Rocket Pool Wallet API](https://apis.io/apis/rocket-pool/rocket-pool-wallet-api/) — The Wallet API from Rocket Pool — 4 operation(s) for wallet.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Rocket Pool Agentic Access](https://apis.io/agentic-access/rocket-pool/rocket-pool-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [RocketPoolMinipool](https://apis.io/schemas/rocket-pool/rocket-pool-minipool/)
- [RocketPoolNode](https://apis.io/schemas/rocket-pool/rocket-pool-node/)
- [RocketPoolRewardsInterval](https://apis.io/schemas/rocket-pool/rocket-pool-rewards-interval/)

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Rocket Pool Minipool Structure](https://apis.io/json-structure/rocket-pool/rocket-pool-minipool-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Rocket Pool Context](https://apis.io/jsonld/rocket-pool/rocket-pool-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Rocket Pool Vocabulary](https://apis.io/vocabularies/rocket-pool/rocket-pool-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Rocket Pool Minipool Status Example](https://apis.io/examples/rocket-pool/rocket-pool-minipool-status-example/)
- [Rocket Pool Network Stats Example](https://apis.io/examples/rocket-pool/rocket-pool-network-stats-example/)
- [Rocket Pool Rewards Status Example](https://apis.io/examples/rocket-pool/rocket-pool-rewards-status-example/)

#### Collections (16)

Postman and Open Collection request collections.

- [Rocket Pool Protocol API (rocketpool-go) Auction API](https://apis.io/collections/rocket-pool/open-rocket-pool-auction-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Deposit API](https://apis.io/collections/rocket-pool/open-rocket-pool-deposit-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Megapool API](https://apis.io/collections/rocket-pool/open-rocket-pool-megapool-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Minipool API](https://apis.io/collections/rocket-pool/open-rocket-pool-minipool-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Network API](https://apis.io/collections/rocket-pool/open-rocket-pool-network-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Node API](https://apis.io/collections/rocket-pool/open-rocket-pool-node-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction OracleDAO API](https://apis.io/collections/rocket-pool/open-rocket-pool-oracledao-api/)
- [Rocket Pool Protocol API (rocketpool-go)](https://apis.io/collections/rocket-pool/open-rocket-pool-protocol/)
- [Rocket Pool Protocol API (rocketpool-go) Auction ProtocolDAO API](https://apis.io/collections/rocket-pool/open-rocket-pool-protocoldao-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Queue API](https://apis.io/collections/rocket-pool/open-rocket-pool-queue-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Rewards API](https://apis.io/collections/rocket-pool/open-rocket-pool-rewards-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Service API](https://apis.io/collections/rocket-pool/open-rocket-pool-service-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Settings API](https://apis.io/collections/rocket-pool/open-rocket-pool-settings-api/)
- [Rocket Pool Smart Node Daemon API](https://apis.io/collections/rocket-pool/open-rocket-pool-smart-node/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Tokens API](https://apis.io/collections/rocket-pool/open-rocket-pool-tokens-api/)
- [Rocket Pool Protocol API (rocketpool-go) Auction Wallet API](https://apis.io/collections/rocket-pool/open-rocket-pool-wallet-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Rocket Pool — jsonschema rules](https://apis.io/rules/rocket-pool/rocket-pool-jsonschema-spectral-rules/)
- [Rocket Pool — smart node rules](https://apis.io/rules/rocket-pool/rocket-pool-smart-node-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Rocket Pool Domain Security](https://apis.io/security/rocket-pool/rocket-pool-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://rocketpool.net)
- [Documentation](https://docs.rocketpool.net)
- [Getting started](https://docs.rocketpool.net/guides/staking/overview)
- [Blog](https://rocketpool.net/blog/)
- [GitHub](https://github.com/rocket-pool)

## API Evangelist rating

**Kin Score 19.2** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 42.7 |
| Contract governance | 27.3 |
| Operational transparency | 2.6 |
| Developer ergonomics | 14.3 |
| Access clarity | 0.0 |

**Agent readiness 14.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
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

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rocket-pool/](https://apis.io/providers/rocket-pool/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rocket Pool: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rocket-pool/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
