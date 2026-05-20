# Unified Asset Identifiers

This document describes a standard for uniquely identifying all assets worldwide.

![Unified Asset Identifier Structure](diagrams/uaid-structure.svg)

A Unified Asset Identifier (UAID) consists of three or more colon-delimited parts.

| Part | Name | Description |
| ------------ | ------------ | ------------ |
| 1. | Scheme | The URI Scheme identifier, always `uaid`.  |
| 2. | Standard | The abbreviated name of the identifying standard. [List of available standards](/standards). |
| 3..n | Standard-specific Identifier | The identifier of the asset as defined by the respective standard.  |

All parts are case insensitive, but lower case is recommended.

### Examples

| AID | What it is |
| ------------ | ------------ |
| **`uaid:iso4217:usd`** | The U.S. Dollar |
| **`uaid:iso4217:xau`** | Gold |
| **`uaid:isin:us0231351067`** | Stock shares of Amazon.com, Inc.  |
| **`uaid:ric:msft.oq`** | Stock shares of Microsoft Corp. traded on the NASDAQ |
| **`uaid:caip19:xrpl:0/slip44:144`** | The native XRP token on the XRP Ledger Livenet |
| **`uaid:caip19:xrpl:1/slip44:144`** | The native XRP token on the XRP Ledger Testnet |
| **`uaid:stablecoin:usdc`** | The Circle USD stablecoin |
| **`uaid:caip19:eip155:1/erc20:0xa0b86991c62`<br>`18b36c1d19d4a2e9eb0ce3606eb48`** | The Circle USD stablecoin issued on the Ethereum Mainnet |
| **`uaid:caip19:tron:0x2b6653dc/trc20:TR7NHq`<br>`jeKQxGTCi8q8ZY4pL8otSzgjLj66`** | The Circle USD stablecoin issued on the Tron Mainnet |
| **`uaid:caip19:eip155:56/erc20:0x55d398326f`<br>`99059ff775485246999027b3197955`** | Wrapped Ethereum issued on the Binance Smart Chain Mainnet |

## Hierarchy

![Unified Asset Identifiers Hierarchy](diagrams/uaid-hierarchy.svg)

Unified Asset Identifiers can be chained hierarchically IF, and only if, the asset is an IOU of its parent, that is

<ol type="a">
<li>Fully redeemable into its parent asset</li><li>Not a financial derivative</li><li>Redeemable at all times</li>
</ol>

Effectively only if it is *"as good as"* its parent asset. Differences in exchange rates between child and parent asset may still apply due to different units of measurement or temporary redemption frictions.