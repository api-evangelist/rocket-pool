# Rocket Pool (rocket-pool)

Rocket Pool is a decentralized Ethereum liquid staking protocol that lets anyone participate in Ethereum proof-of-stake without running a full 32 ETH validator. Stakers deposit ETH and receive rETH, a rebasing-free yield-bearing liquid staking token that automatically accrues consensus and execution layer rewards and is freely composable across DeFi. On the supply side, permissionless node operators can run a Rocket Pool minipool with as little as 8 ETH (and a smaller RPL bond) — Rocket Pool pairs operator ETH with the rETH-backed deposit pool to fund full beacon-chain validators, and operators earn consensus rewards plus a commission from rETH users and RPL inflation rewards. The protocol is governed on-chain through the Protocol DAO (pDAO) and the Oracle DAO (oDAO) and is specified by Rocket Pool Improvement Proposals (RPIPs). The reference node software stack is the Smart Node (rocketpool CLI plus a Go daemon) distributed as Docker images, alongside Go and TypeScript/JavaScript libraries (rocketpool-go, rocketpool-js) for reading and writing protocol state directly against the Rocket Pool smart contracts on Ethereum mainnet. Rocket Pool has no centralized REST API, no hosted developer platform, no API keys, and no pricing — all participation is on-chain via Ethereum JSON-RPC and the protocol's deployed contracts.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rocket-pool/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rocket-pool/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Blockchain
- Ethereum
- Liquid Staking
- Proof of Stake
- DeFi
- Smart Contracts
- Node Operators
- Validator
- rETH
- RPL
- Minipool
- Decentralized Finance
- Decentralized Governance
- DAO
- Web3

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Rocket Pool Smart Node Daemon API

The Smart Node daemon API is the local HTTP/IPC interface exposed by the rocketpool-daemon Go service that ships with the Smart Node Docker stack. The rocketpool CLI uses this API to manage node operator wallets, minipools, megapools, RPL staking, rewards claims, smoothing pool participation, and protocol/oracle DAO interactions. It is local-only, authenticated by filesystem access, and is the contract between the CLI front-end and the long-running node service.

- **Human URL:** [https://github.com/rocket-pool/smartnode](https://github.com/rocket-pool/smartnode)

#### Tags

- Smart Node
- Node Operator
- CLI
- Minipool
- Megapool
- Wallet
- Rewards
- DAO

#### Properties

- [Source Code](https://github.com/rocket-pool/smartnode)
- [Documentation](https://docs.rocketpool.net/guides/node/responsibilities)
- [OpenAPI](openapi/rocket-pool-smart-node-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rocket-pool-smart-node.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rocket-pool-smart-node.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](rules/rocket-pool-smart-node-rules.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

### Rocket Pool Protocol API (rocketpool-go)

The rocketpool-go library is a Golang client that wraps the Rocket Pool smart contracts deployed on Ethereum and exposes a typed protocol API for reading and writing network state: deposit pool, minipools, megapools, node registrations, RPL staking, rewards trees, auctions, oracle DAO, protocol DAO, tokens (rETH, RPL), and protocol settings. It is the canonical Go interface to the protocol and is used by the Smart Node, by Oracle DAO tooling, and by third-party integrators.

- **Human URL:** [https://github.com/rocket-pool/rocketpool-go](https://github.com/rocket-pool/rocketpool-go)

#### Tags

- Smart Contracts
- Go
- Library
- Protocol
- rETH
- RPL
- Minipool
- Auction
- DAO

#### Properties

- [Source Code](https://github.com/rocket-pool/rocketpool-go)
- [Documentation](https://docs.rocketpool.net/overview/contracts-integrations)
- [OpenAPI](openapi/rocket-pool-protocol-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/rocket-pool-protocol.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rocket-pool-protocol.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rocket Pool Protocol API (rocketpool-js)

The rocketpool-js library is a TypeScript/JavaScript client for the Rocket Pool protocol's deployed smart contracts. It mirrors much of the Go library's surface and is intended for browser-based dApps, indexer services, and integrations such as DeFi front-ends that need to read rETH state or submit user deposits.

- **Human URL:** [https://github.com/rocket-pool/rocketpool-js](https://github.com/rocket-pool/rocketpool-js)

#### Tags

- Smart Contracts
- TypeScript
- JavaScript
- Library
- rETH
- dApp

#### Properties

- [Source Code](https://github.com/rocket-pool/rocketpool-js)
- [SDK](https://www.npmjs.com/package/@rocket-pool/contracts)
- [Postman Collection](collections/rocket-pool-protocol.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rocket-pool-protocol.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/rocket-pool-smart-node.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rocket-pool-smart-node.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://rocketpool.net)
- [Documentation](https://docs.rocketpool.net)
- [Getting Started](https://docs.rocketpool.net/guides/staking/overview)
- [Node Operator Guide](https://docs.rocketpool.net/guides/node/intro)
- [Overview](https://docs.rocketpool.net/overview/)
- [Contracts And Integrations](https://docs.rocketpool.net/overview/contracts-integrations)
- [GitHub Organization](https://github.com/rocket-pool)
- [Source Code](https://github.com/rocket-pool/rocketpool)
- [Smart Node](https://github.com/rocket-pool/smartnode)
- [Smart Node Installer](https://github.com/rocket-pool/smartnode-install)
- [Go S D K](https://github.com/rocket-pool/rocketpool-go)
- [Java Script S D K](https://github.com/rocket-pool/rocketpool-js)
- [Node Manager Core](https://github.com/rocket-pool/node-manager-core)
- [Oracle D A O Tool](https://github.com/rocket-pool/odaotool)
- [Tree Gen](https://github.com/rocket-pool/treegen)
- [Router](https://github.com/rocket-pool/rocketpool-router)
- [Subgraph](https://github.com/rocket-pool/rocket-pool-subgraph)
- [Improvements](https://github.com/rocket-pool/RPIPs)
- [Research](https://github.com/rocket-pool/rocketpool-research)
- [Snapshot Strategies](https://github.com/rocket-pool/snapshot-strategies)
- [Ledger Plugin](https://github.com/rocket-pool/ledger-app-plugin-rocketpool)
- [Docker Images](https://hub.docker.com/u/rocketpool)
- [Governance Forum](https://dao.rocketpool.net)
- [Twitter](https://twitter.com/Rocket_Pool)
- [Discord](https://discord.gg/rocketpool)
- [License](https://github.com/rocket-pool/rocketpool/blob/master/LICENSE)
- [JSON Schema](json-schema/rocket-pool-minipool-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/rocket-pool-minipool-structure.json)
- [JSON-LD](json-ld/rocket-pool-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Vocabulary](vocabulary/rocket-pool-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
