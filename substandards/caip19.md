# UAID x CAIP-19 - Chain Agnostic Asset Identifiers

CAIP-19 defines a way to identify a type of asset (e.g. Bitcoin, Ether, ATOM) with an optional asset identifier suffix (for individually-addressable tokens like NFTs) in a human-readable, developer- and transaction-friendly way.

https://standards.chainagnostic.org/CAIPs/caip-19

### Examples

| UAID | What it is |
| ------------ | ------------ |
| **`uaid:caip19:bip122:000000000019d6689c`<br>`085ae165831e93/slip44:0`** | Native BTC on the Bitcoin Mainnet |
| **`uaid:caip19:eip155:1/slip44:60`** | The native ETH token on the Ethereum Mainnet |
| **`uaid:caip19:xrpl:0/slip44:144`** | The native XRP token on the XRP Ledger Livenet |
| **`uaid:caip19:stellar:pubnet/slip44:148`** | The native XLM token on the Stellar Pubnet |
| **`uaid:caip19:eip155:1/erc20:0xdac17f95`<br>`8d2ee523a2206206994597c13d831ec7`** | Tether USD (USDT) on Ethereum Mainnet as an ERC-20 token |
| **`uaid:caip19:solana:5eykt4UsFv8P8NJdTR`<br>`EpY1vzqKQZKvdp/token:EPjFWdd5AufqSSq`<br>`eM2qN1xzybapC8G4wEGGkZwyTDt1v`** | USD Coin (USDC) on Solana Mainnet |
| **`uaid:caip19:tron:0x2b6653dc/trc20:TR7`<br>`NHqjeKQxGTCi8q8ZY4pL8otSzgjLj6t`** | Tether USD (USDT) on TRON Mainnet as a TRC-20 token |