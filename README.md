# @luxexchange/contracts

Solidity token contracts for the Lux Exchange ecosystem.

These are Lux-original contracts, extracted from the Lux Exchange monorepo
so the non-GPL Solidity sources live independently of the Uniswap-derived
(GPL) parts of the exchange.

## Contracts

| Contract | Description |
|----------|-------------|
| `LuxToken.sol` | Mintable ERC20 used for bridged Lux ecosystem assets (LETH, LBTC, LUSD, ...). Owner-gated `mint`, holder `burn`, infinite-allowance optimization. |
| `WLUX.sol` | Wrapped LUX — standard ERC20 wrapper for the native LUX token. `deposit`/`withdraw`, `totalSupply` tracks the contract's native balance. |

Both target Solidity `^0.8.20`.

## License

MIT — see [LICENSE](./LICENSE).
