# Level

Level is a stablecoin protocol that issued **lvlUSD**, a stablecoin fully backed by USDC and USDT which were deployed into blue-chip lending protocols (Aave and the Morpho Steakhouse USDC vault) to generate yield. Lending yield was returned to holders through an ERC-4626 staking mechanism — lvlUSD staked for **slvlUSD**, a yield-accruing token that appreciates as the protocol distributes yield into the staking contract. Both tokens were transferable and integrated across DeFi venues including Morpho, Pendle, Spectra and Curve, with LayerZero OFT adapters bridging them to Base.

Level publishes **no HTTP API**. Its programmable surface is a set of audited Ethereum mainnet smart contracts (lvlUSD, slvlUSD, LevelMinting, LevelStakingPool, LevelUsdPointsFarm, LevelReserveLens) documented in GitBook and published at [github.com/Level-Money](https://github.com/Level-Money).

## Status: sunset

In September 2025 the Level team announced it was joining the Sky (fka MakerDAO) ecosystem as part of Grove, and that the Level protocol is being sunset — mints paused, redemptions made public and fixed 1:1, cooldowns cut to two seconds, final yield distribution on 2025-10-02, and the front end retired on 2025-12-15. Redemption by calling the contracts directly remains available. See `lifecycle/level-lifecycle.yml`.

## Disambiguation

This repo profiles **Level (level.money)** — the lvlUSD stablecoin protocol backed by Polychain Capital, Dragonfly and BFC. The `lightspeed-venture-partners` portfolio entry at <https://lsvp.com/company/level/> refers to a **different** company also named Level (level.com), a 2018 benefits/insurance fintech. As of 2026-07-19 `level.com` resolves no A record and `levelbenefits.com` serves a parked "Launching Soon" page, so that company has no verifiable public surface to profile. The two were collapsed onto one slug by the VC-portfolio stub generator.

## Artifacts

| Artifact | File |
|---|---|
| llms.txt (verbatim) | `llms/level-llms.txt` |
| Well-known probe | `well-known/level-well-known.yml` |
| Lifecycle / sunset | `lifecycle/level-lifecycle.yml` |
| Conformance | `conformance/level-conformance.yml` |
| Vulnerability disclosure + audits | `security/level-vulnerability-disclosure.yml` |
| Domain security | `security/level-domain-security.yml` |

Backed by: lightspeed-venture-partners (see disambiguation), polychain
