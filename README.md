# Rocket Pool

Rocket Pool is a decentralized Ethereum liquid staking protocol. Stakers deposit ETH and receive **rETH**, a non-rebasing yield-bearing token. Permissionless node operators run a Smart Node and pair as little as 8 ETH (plus an RPL bond) with rETH-user ETH to fund full beacon-chain validators, earning consensus rewards plus commission plus RPL inflation. Governance happens on-chain through the Protocol DAO and Oracle DAO; specifications live in the [RPIPs](https://github.com/rocket-pool/RPIPs) repo.

There is no centralized REST API, no hosted developer platform, no API keys, and no pricing surface — all participation is on-chain via Ethereum JSON-RPC against the protocol's smart contracts.

## Surface this repo profiles

| Artifact | Description |
|---|---|
| [apis.yml](apis.yml) | Top-level provider profile and API inventory |
| [openapi/rocket-pool-smart-node-openapi.yml](openapi/rocket-pool-smart-node-openapi.yml) | Smart Node daemon HTTP API (the local API behind the rocketpool CLI) |
| [openapi/rocket-pool-protocol-openapi.yml](openapi/rocket-pool-protocol-openapi.yml) | rocketpool-go protocol read surface, modeled as HTTP |
| [json-schema/](json-schema) | Minipool, Node, and Rewards-Interval JSON Schemas |
| [json-structure/](json-structure) | JSON-Structure form of the Minipool entity |
| [json-ld/rocket-pool-context.jsonld](json-ld/rocket-pool-context.jsonld) | JSON-LD context for Rocket Pool entities |
| [capabilities/](capabilities) | Naftiko capability workflows: node-operations, protocol-read, rewards-claim |
| [examples/](examples) | Representative response payloads |
| [rules/rocket-pool-smart-node-rules.yml](rules/rocket-pool-smart-node-rules.yml) | Spectral ruleset enforcing Rocket Pool API conventions |
| [vocabulary/rocket-pool-vocabulary.yml](vocabulary/rocket-pool-vocabulary.yml) | Domain vocabulary (rETH, RPL, minipool, megapool, smoothing pool, RPIP) |

## Upstream sources

- Website: <https://rocketpool.net>
- Docs: <https://docs.rocketpool.net>
- GitHub org: <https://github.com/rocket-pool>
- Protocol contracts: <https://github.com/rocket-pool/rocketpool>
- Smart Node (Go CLI + daemon): <https://github.com/rocket-pool/smartnode>
- Smart Node installer: <https://github.com/rocket-pool/smartnode-install>
- Go bindings: <https://github.com/rocket-pool/rocketpool-go>
- JavaScript/TypeScript bindings: <https://github.com/rocket-pool/rocketpool-js>
- Node Manager Core: <https://github.com/rocket-pool/node-manager-core>
- Improvement proposals: <https://github.com/rocket-pool/RPIPs>
- Research: <https://github.com/rocket-pool/rocketpool-research>
- Subgraph: <https://github.com/rocket-pool/rocket-pool-subgraph>
- Router: <https://github.com/rocket-pool/rocketpool-router>
- L2 oracles: arbitrum, polygon, zksync, scroll variants under `rocket-pool/rocketpool-*-oracle`

## License

Upstream Rocket Pool code is GPL-3.0. This profile is published under the same terms as other api-evangelist provider profiles.
