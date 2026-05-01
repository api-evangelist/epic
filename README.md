# Epic Games (epic)

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
