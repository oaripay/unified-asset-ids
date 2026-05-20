# Unified Asset Identifiers

This document describes a standard for uniquely identifying all assets worldwide.

![Unified Asset Identifier Structure](diagrams/aid-structure.svg)

A Unified Asset Identifier consists of three or more colon-delimited parts.

| Part | Name | Description |
| ------------ | ------------ | ------------ |
| 1. | Scheme | The URI Scheme identifier, always `aid`  |
| 2. | Standard | The standard identifier. [List of available standards](/standards) |
| 3..n | Identifier | The standard-specific identifier of the asset. Its shape is fully defined by the respective standard.  |

All parts are case insensitive, but lower case is recommended.

### Examples

| AID | What it is |
| ------------ | ------------ |
| **`aid:iso4217:usd`** | The U.S. Dollar |
| **`aid:iso4217:xau`** | Gold |
| **`aid:isin:us0231351067`** | Stock shares of Amazon.com, Inc.  |
| **`aid:ric:msft.oq`** | Stock shares of Microsoft Corp. traded on the NASDAQ |
| **`aid:caip19:xrpl:0/slip44:144`** | The native XRP token on the XRP Ledger Livenet |
| **`aid:caip19:xrpl:1/slip44:144`** | The native XRP token on the XRP Ledger Testnet |
| **`aid:stablecoin:usdc`** | The Circle USD stablecoin |
| **`aid:caip19:eip155:1/erc20:0xa0b86991c62`<br>`18b36c1d19d4a2e9eb0ce3606eb48`** | The Circle USD stablecoin issued on the Ethereum Mainnet |
| **`aid:caip19:tron:0x2b6653dc/trc20:TR7NHq`<br>`jeKQxGTCi8q8ZY4pL8otSzgjLj66`** | The Circle USD stablecoin issued on the Tron Mainnet |
| **`aid:caip19:eip155:56/erc20:0x55d398326f`<br>`99059ff775485246999027b3197955`** | Wrapped Ethereum issued on the Binance Smart Chain Mainnet |

### Identifiers Can Be Stacked

![Unified Asset Identifiers Stacked](diagrams/aid-hierarchy.svg)

Unified Asset Identifiers can be chained hierarchically IF, and only if, the asset is an IOU of its parent, that is

<ol type="a">
<li>Fully redeemable into its parent asset</li><li>Not a financial derivative</li><li>Redeemable at all times</li>
</ol>

Effectively only if it is *"as good as"* its parent asset. Differences in exchange rates between child and parent asset may still apply due to different units of measurement or temporary redemption frictions.