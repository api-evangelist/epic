# Epic Games (epic)

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

Epic Games operates the Epic Games Store digital storefront and the Epic Online Services (EOS) platform, providing developers with cross-platform game services. Epic Online Services is a free SDK based on Fortnite's backend infrastructure, supporting matchmaking, friends, leaderboards, achievements, voice chat, anti-cheat, and player data storage across Windows, macOS, PlayStation, Xbox, Nintendo Switch, iOS, and Android. The Epic Account Services and EOS Web APIs deliver authentication, account management, ecommerce, and analytics for games published on the Epic Games Store and other platforms.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/epic/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Partner

## Tags

- Game Services, Gaming, Cross-Platform, Achievements, Leaderboards, Matchmaking, Anti-Cheat, OAuth2

## Timestamps

- **Created:** 2024-07-02
- **Modified:** 2026-04-28

## APIs

### Epic Account Services API
Epic Account Services (EAS) provides authentication and identity for players using Epic Games accounts. Supports OAuth 2.0 authorization code, device, and exchange code flows, account info retrieval, and single sign-on across Epic Games Store and partner titles.

**Human URL:** [https://dev.epicgames.com/docs/epic-account-services](https://dev.epicgames.com/docs/epic-account-services)

#### Tags

- Authentication, OAuth2, Identity, Single Sign-On

#### Properties

- [Documentation](https://dev.epicgames.com/docs/epic-account-services)
- [Authentication](https://dev.epicgames.com/docs/epic-account-services/auth/auth-interface)
- [GettingStarted](https://dev.epicgames.com/docs/epic-account-services/getting-started)

### Epic Online Services Achievements API
The EOS Achievements API enables developers to define, unlock, and query player achievements across platforms. Supports definitions, player progress, and unlocking via the EOS SDK or Web API.

**Human URL:** [https://dev.epicgames.com/docs/game-services/achievements](https://dev.epicgames.com/docs/game-services/achievements)

#### Tags

- Achievements, Game Services, Progression

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/achievements)

### Epic Online Services Leaderboards API
The EOS Leaderboards API provides global and per-friend leaderboards backed by player stats. Developers configure leaderboards in the developer portal and query rankings via the EOS SDK or Web API.

**Human URL:** [https://dev.epicgames.com/docs/game-services/leaderboards](https://dev.epicgames.com/docs/game-services/leaderboards)

#### Tags

- Leaderboards, Game Services, Stats

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/leaderboards)

### Epic Online Services Stats API
The EOS Stats API tracks player statistics over time, providing the data source that powers leaderboards and achievements. Supports ingest, increment, and query operations on stat values.

**Human URL:** [https://dev.epicgames.com/docs/game-services/eos-stats-interface](https://dev.epicgames.com/docs/game-services/eos-stats-interface)

#### Tags

- Stats, Game Services, Telemetry

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/eos-stats-interface)

### Epic Online Services Friends API
The EOS Friends API exposes a player's Epic Games friends list, allowing games to surface social presence, invitations, and party formation across platforms.

**Human URL:** [https://dev.epicgames.com/docs/epic-account-services/eos-friends-interface](https://dev.epicgames.com/docs/epic-account-services/eos-friends-interface)

#### Tags

- Friends, Social, Game Services

#### Properties

- [Documentation](https://dev.epicgames.com/docs/epic-account-services/eos-friends-interface)

### Epic Online Services Ecom API
The EOS Ecom (Ecommerce) Interface API exposes the player's Epic Games Store entitlements, ownership, catalog offers, and checkout flows. Used by titles published on the Epic Games Store to verify purchases and unlock downloadable content.

**Human URL:** [https://dev.epicgames.com/docs/epic-games-store/services/ecom/ecom-overview](https://dev.epicgames.com/docs/epic-games-store/services/ecom/ecom-overview)

#### Tags

- Ecommerce, Entitlements, Catalog, Epic Games Store

#### Properties

- [Documentation](https://dev.epicgames.com/docs/epic-games-store/services/ecom/ecom-overview)

### Epic Online Services Lobby and Sessions API
The EOS Lobby and Sessions APIs provide matchmaking primitives for multiplayer games, including lobby creation, joining, attribute filtering, and dedicated session management.

**Human URL:** [https://dev.epicgames.com/docs/game-services/lobbies-and-sessions](https://dev.epicgames.com/docs/game-services/lobbies-and-sessions)

#### Tags

- Matchmaking, Lobbies, Sessions, Multiplayer

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/lobbies-and-sessions)

### Epic Online Services Player Data Storage API
The EOS Player Data Storage and Title Storage APIs persist per-player save data and shared title-level configuration in the cloud, with cross-platform availability and versioning.

**Human URL:** [https://dev.epicgames.com/docs/game-services/player-data-storage](https://dev.epicgames.com/docs/game-services/player-data-storage)

#### Tags

- Storage, Cloud Saves, Game Services

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/player-data-storage)

### Epic Online Services Anti-Cheat API
Easy Anti-Cheat (EAC) integrated into Epic Online Services provides kernel and user-mode anti-cheat protections, server-side validation, and reporting tooling for cross-platform multiplayer titles.

**Human URL:** [https://dev.epicgames.com/docs/game-services/anti-cheat](https://dev.epicgames.com/docs/game-services/anti-cheat)

#### Tags

- Anti-Cheat, Security, Multiplayer

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/anti-cheat)

### Epic Online Services Voice API
The EOS Voice Interface delivers in-game voice chat using Vivox backend infrastructure, with positional audio, room management, and moderation controls across platforms.

**Human URL:** [https://dev.epicgames.com/docs/game-services/eos-voice-interface](https://dev.epicgames.com/docs/game-services/eos-voice-interface)

#### Tags

- Voice, Chat, Communications, Vivox

#### Properties

- [Documentation](https://dev.epicgames.com/docs/game-services/eos-voice-interface)

## Common Properties

- [Website](https://www.epicgames.com/)
- [Portal](https://dev.epicgames.com/portal/)
- [Documentation](https://dev.epicgames.com/docs/)
- [GettingStarted](https://dev.epicgames.com/docs/epic-online-services/eos-get-started)
- [Authentication](https://dev.epicgames.com/docs/epic-account-services/auth/auth-interface)
- [TermsOfService](https://dev.epicgames.com/services-agreement)
- [PrivacyPolicy](https://www.epicgames.com/site/en-US/privacypolicy)
- [Support](https://dev.epicgames.com/community/)
- [Store](https://store.epicgames.com/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
