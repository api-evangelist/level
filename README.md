# Level

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
