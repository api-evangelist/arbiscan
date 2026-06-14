# Arbiscan

Arbiscan is the official blockchain explorer, search, API, and analytics platform for Arbitrum One, the leading Ethereum Layer 2 scaling network. It enables developers and users to query Arbitrum One transaction histories, token transfers (ERC-20, ERC-721, ERC-1155), smart contract source code and ABIs, block data, and L2 network statistics.

The Arbiscan API is part of the Etherscan unified V2 platform, accessible across 60+ EVM-compatible chains with a single API key using chainid 42161 for Arbitrum One.

**Base URL:** `https://api.etherscan.io/v2/api` (with `chainid=42161`)

**Documentation:** https://docs.arbiscan.io/

**Pricing:** https://arbiscan.io/apis

## APIs

- **Arbiscan API** - REST API for querying Arbitrum One blockchain data including accounts, transactions, tokens, contracts, blocks, logs, and L2 network statistics.

## Resources

- [apis.yml](apis.yml) - APIs.json 0.19 provider index
- [plans/arbiscan-plans-pricing.yml](plans/arbiscan-plans-pricing.yml) - API Commons Plans definition
- [rate-limits/arbiscan-rate-limits.yml](rate-limits/arbiscan-rate-limits.yml) - Rate limit definitions per tier
- [finops/arbiscan-finops.yml](finops/arbiscan-finops.yml) - FinOps Framework / FOCUS cost mapping
