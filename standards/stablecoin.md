# UAID x Stablecoins

This standard defines an abstract type of asset that represents all issued stablecoins from the same issuer with the same underlying `iso4217` currency.

The benefit of this abstraction is that a payment recipient can request to be paid in a specific stablecoin without having to specify the chain.

## List of Stablecoins

| UAID | Stablecoin |
| ------------ | ------------ |
| **`uaid:stablecoin:usdt`** | Tether USD (USDT) |
| **`uaid:stablecoin:usdc`** | Circle USD (USDC) |
| **`uaid:stablecoin:usdt`** | Tether USDt (USDT) |
| **`uaid:stablecoin:usdc`** | USD Coin (USDC) |
| **`uaid:stablecoin:usds`** | Sky Dollar (USDS) |
| **`uaid:stablecoin:usd1`** | World Liberty Financial USD (USD1) |
| **`uaid:stablecoin:dai`** | Dai (DAI) |
| **`uaid:stablecoin:usde`** | Ethena USDe (USDE) |
| **`uaid:stablecoin:pyusd`** | PayPal USD (PYUSD) |
| **`uaid:stablecoin:buidl`** | BlackRock USD Institutional Digital Liquidity Fund (BUIDL) |
| **`uaid:stablecoin:usyc`** | Circle USYC (USYC) |
| **`uaid:stablecoin:usdg`** | Global Dollar (USDG) |
| **`uaid:stablecoin:usdy`** | Ondo US Dollar Yield (USDY) |
| **`uaid:stablecoin:falconusdf`** | Falcon USD (USDF) |
| **`uaid:stablecoin:rlusd`** | Ripple USD (RLUSD) |
| **`uaid:stablecoin:usdd`** | USDD (USDD) |
| **`uaid:stablecoin:bfusd`** | BFUSD (BFUSD) |
| **`uaid:stablecoin:usdtb`** | USDtb (USDTB) |
| **`uaid:stablecoin:u`** | United Stables (U) |
| **`uaid:stablecoin:gho`** | GHO (GHO) |
| **`uaid:stablecoin:usd0`** | Usual USD (USD0) |
| **`uaid:stablecoin:ylds`** | YLDS (YLDS) |
| **`uaid:stablecoin:tusd`** | TrueUSD (TUSD) |
| **`uaid:stablecoin:apxusd`** | apxUSD (APXUSD) |
| **`uaid:stablecoin:a7a5`** | A7A5 (A7A5) |
| **`uaid:stablecoin:eurc`** | EURC (EURC) |
| **`uaid:stablecoin:fdusd`** | First Digital USD (FDUSD) |
| **`uaid:stablecoin:usx`** | Solstice USX (USX) |
| **`uaid:stablecoin:polypusd`** | Polymarket USD (PUSD) |
| **`uaid:stablecoin:busd`** | Binance USD (BUSD) |
| **`uaid:stablecoin:frax`** | Legacy Frax Dollar (FRAX) |
| **`uaid:stablecoin:royaldollar`** | Royal Dollar (RUSD) |
| **`uaid:stablecoin:megausdm`** | MegaUSD (USDM) |
| **`uaid:stablecoin:crvusd`** | crvUSD (CRVUSD) |
| **`uaid:stablecoin:usdaangle`** | USDa (USDA) |
| **`uaid:stablecoin:satusd`** | Satoshi Stablecoin (SATUSD) |
| **`uaid:stablecoin:eurs`** | STASIS EURO (EURS) |
| **`uaid:stablecoin:usat`** | USA₮ (USAT) |
| **`uaid:stablecoin:gategusd`** | GUSD (GUSD) |
| **`uaid:stablecoin:nusd`** | Neutrl USD (NUSD) |
| **`uaid:stablecoin:mim`** | Magic Internet Money (MIM) |
| **`uaid:stablecoin:ausd`** | AUSD (AUSD) |
| **`uaid:stablecoin:frxusd`** | Frax USD (FRXUSD) |
| **`uaid:stablecoin:eurcv`** | EUR CoinVertible (EURCV) |
| **`uaid:stablecoin:cash`** | CASH (CASH) |
| **`uaid:stablecoin:asterusdf`** | Aster USDF (USDF) |
| **`uaid:stablecoin:capusd`** | Cap USD (CUSD) |
| **`uaid:stablecoin:usdat`** | Saturn Dollar (USDAT) |
| **`uaid:stablecoin:palmpusd`** | Palm USD (PUSD) |
| **`uaid:stablecoin:dusd`** | StandX DUSD (DUSD) |
| **`uaid:stablecoin:mnee`** | MNEE USD Stablecoin (MNEE) |
| **`uaid:stablecoin:unityuusd`** | Unity USD (UUSD) |
| **`uaid:stablecoin:avusd`** | Avant USD (AVUSD) |
| **`uaid:stablecoin:pmusd`** | Precious Metals USD (PMUSD) |
| **`uaid:stablecoin:jusd`** | JUSD (JUSD) |
| **`uaid:stablecoin:usda`** | USDA (USDA) |
| **`uaid:stablecoin:mainmsusd`** | Main Street USD (MSUSD) |
| **`uaid:stablecoin:must`** | Mustang (MUST) |
| **`uaid:stablecoin:lisusd`** | Lista USD (LISUSD) |
| **`uaid:stablecoin:cgusd`** | Cygnus Finance Global USD (CGUSD) |
| **`uaid:stablecoin:feusd`** | Felix feUSD (FEUSD) |
| **`uaid:stablecoin:brlv`** | Crown BRLV (BRLV) |
| **`uaid:stablecoin:fxusd`** | f(x) Protocol fxUSD (FXUSD) |
| **`uaid:stablecoin:dola`** | DOLA (DOLA) |
| **`uaid:stablecoin:usdx`** | USDX (USDX) |
| **`uaid:stablecoin:eure`** | Monerium EURe (EURE) |
| **`uaid:stablecoin:usdon`** | Ondo U.S. Dollar Token (USDON) |
| **`uaid:stablecoin:euri`** | Eurite (EURI) |
| **`uaid:stablecoin:jpyc`** | JPY Coin (JPYC) |
| **`uaid:stablecoin:jupusd`** | JupUSD (JUPUSD) |
| **`uaid:stablecoin:xusd`** | StraitsX XUSD (XUSD) |
| **`uaid:stablecoin:brz`** | Brazilian Digital Token (BRZ) |
| **`uaid:stablecoin:fidd`** | Fidelity Digital Dollar (FIDD) |
| **`uaid:stablecoin:usdkg`** | USDKG (USDKG) |
| **`uaid:stablecoin:ausdt`** | Alloy by Tether (AUSDT) |
| **`uaid:stablecoin:aegisyusd`** | Aegis YUSD (YUSD) |
| **`uaid:stablecoin:tgbp`** | Tokenised GBP (TGBP) |
| **`uaid:stablecoin:yzusd`** | Yuzu USD (YZUSD) |
| **`uaid:stablecoin:zchf`** | Frankencoin (ZCHF) |
| **`uaid:stablecoin:usdp`** | Pax Dollar (USDP) |
| **`uaid:stablecoin:gemgusd`** | Gemini Dollar (GUSD) |
| **`uaid:stablecoin:brla`** | BRLA Digital (BRLA) |
| **`uaid:stablecoin:metamaskmusd`** | MetaMask USD (MUSD) |
| **`uaid:stablecoin:ustc`** | TerraClassicUSD (USTC) |
| **`uaid:stablecoin:reusd`** | Resupply USD (REUSD) |
| **`uaid:stablecoin:usdo`** | OpenEden OpenDollar (USDO) |
| **`uaid:stablecoin:xtusd`** | XT Stablecoin XTUSD (XTUSD) |
| **`uaid:stablecoin:bold`** | BOLD (BOLD) |
| **`uaid:stablecoin:mezomusd`** | Mezo USD (MUSD) |
| **`uaid:stablecoin:hbd`** | Hive Dollar (HBD) |
| **`uaid:stablecoin:usn`** | Noon USN (USN) |
| **`uaid:stablecoin:lusd`** | Liquity USD (LUSD) |
| **`uaid:stablecoin:buck`** | BUCK Stablecoin (BUCK) |
| **`uaid:stablecoin:honey`** | Honey (HONEY) |
| **`uaid:stablecoin:electroniceusd`** | Electronic USD (EUSD) |
| **`uaid:stablecoin:metromsusd`** | Metronome Synth USD (MSUSD) |
| **`uaid:stablecoin:usdh`** | USDH (USDH) |
| **`uaid:stablecoin:susd`** | sUSD (SUSD) |
| **`uaid:stablecoin:royaleuro`** | Royal Euro (REUR) |
| **`uaid:stablecoin:xsgd`** | XSGD (XSGD) |
| **`uaid:stablecoin:hyusd`** | Hylo USD (HYUSD) |
| **`uaid:stablecoin:mentousdm`** | Mento Dollar (USDM) |
| **`uaid:stablecoin:wemixdollar`** | WEMIX Dollar (WEMIX$) |
| **`uaid:stablecoin:nobleusdn`** | Noble Dollar (USDN) |
| **`uaid:stablecoin:alusd`** | Alchemix USD (ALUSD) |
| **`uaid:stablecoin:usdm`** | USDM (USDM) |
| **`uaid:stablecoin:eurr`** | StablR Euro (EURR) |
| **`uaid:stablecoin:vcred`** | VCRED (VCRED) |
| **`uaid:stablecoin:sbc`** | Stable Coin (SBC) |
| **`uaid:stablecoin:mai`** | MAI (MIMATIC) |
| **`uaid:stablecoin:suiusde`** | eSui Dollar (SUIUSDE) |
| **`uaid:stablecoin:yusd`** | YUSD Stablecoin (YUSD) |
| **`uaid:stablecoin:hollar`** | Hydrated Dollar (HOLLAR) |
| **`uaid:stablecoin:wusd`** | Worldwide USD (WUSD) |
| **`uaid:stablecoin:youvesuusd`** | youves uUSD (UUSD) |
| **`uaid:stablecoin:idrt`** | Rupiah Token (IDRT) |
| **`uaid:stablecoin:anzensusda`** | Anzens USDA (USDA) |
| **`uaid:stablecoin:eusd`** | eUSD (EUSD) |
