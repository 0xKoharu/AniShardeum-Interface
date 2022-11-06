# AniShardeum Interface

[![Unit Tests](https://github.com/Uniswap/interface/actions/workflows/unit-tests.yaml/badge.svg)](https://github.com/Uniswap/interface/actions/workflows/unit-tests.yaml)
[![Integration Tests](https://github.com/Uniswap/interface/actions/workflows/integration-tests.yaml/badge.svg)](https://github.com/Uniswap/interface/actions/workflows/integration-tests.yaml)
[![Lint](https://github.com/Uniswap/interface/actions/workflows/lint.yml/badge.svg)](https://github.com/Uniswap/interface/actions/workflows/lint.yml)
[![Release](https://github.com/Uniswap/interface/actions/workflows/release.yaml/badge.svg)](https://github.com/Uniswap/interface/actions/workflows/release.yaml)
[![Crowdin](https://badges.crowdin.net/uniswap-interface/localized.svg)](https://crowdin.com/project/uniswap-interface)

An open source interface for AniShardeum -- a protocol for decentralized exchange of Shardeum tokens by 0xKoharu.

- Website: [anishardeum.org](https://anishardeum.org/)
- Interface: [app.anishardeum.org](https://app.uniswap.org)
- Docs: [anishardeum.org/docs/](https://docs.anishardeum.org/)
- Twitter: [@AniShardeum](https://twitter.com/Anishardeum)
- Reddit: [/r/Anishardeum](https://www.reddit.com/r/Anishardeum/)
- Email: [contact@anishardeum.org](mailto:contact@anishardeum.org)
- Discord: [AniShardeum](Coming Soon)
- Whitepapers: 
  - [V1](Coming soon)

## Accessing the AniShardeum Interface

To access the AniShardeum Interface, use an IPFS gateway link from the
[latest release](Coming Soon),
or visit [app.anishardeum.org](https://app.anishardeum.org).

## Unsupported tokens

Check out `useUnsupportedTokenList()` in [src/state/lists/hooks.ts](./src/state/lists/hooks.ts) for blocking tokens in your instance of the interface.

You can block an entire list of tokens by passing in a tokenlist like [here](./src/constants/lists.ts)

## Contributions

For steps on local deployment, development, and code contribution, please see [CONTRIBUTING](./CONTRIBUTING.md).

## Accessing AniShardeum V1

The AniShardeum Interface supports swapping, adding liquidity, removing liquidity and migrating liquidity for AniShardeum protocol V1.

- Swap on Uniswap V2: https://app.anishardeum.org/#/swap?use=v1
- View V2 liquidity: https://app.anishardeum.org/#/pool/v1
- Add V2 liquidity: https://app.anishardeum.org/#/add/v1
- Migrate V2 liquidity to V3: https://app.anishardeum.org/#/migrate/v1

## Accessing Uniswap V1

The Uniswap V1 interface for mainnet and testnets is accessible via IPFS gateways
linked from the [v1.0.0 release](Coming Soon).
