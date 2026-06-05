# Blizzard Entertainment (blizzard-entertainment)

Blizzard Entertainment is an American video game developer and publisher and a subsidiary of Activision Blizzard. Blizzard exposes a Battle.net Developer Portal that provides public OAuth 2.0 protected APIs returning game data and player profile data for its major franchises including World of Warcraft, Diablo III, StarCraft II, and Hearthstone.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/blizzard-entertainment/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider

## Tags

- Games
- Entertainment
- Video Games
- Game Data
- Battle.net

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-19

## APIs

### World of Warcraft Game Data API

Battle.net Game Data API for World of Warcraft providing access to achievements, auctions, characters, guilds, items, mounts, pets, PvP seasons, realms, regions, and other core game data resources for both the retail and classic clients. Endpoints follow the Battle.net regional host pattern (e.g. https://us.api.blizzard.com) and require an OAuth 2.0 client credentials access token. Namespaces (static, dynamic, profile) are passed as query parameters to select the data set.

- **Human URL:** [https://develop.battle.net/documentation/world-of-warcraft](https://develop.battle.net/documentation/world-of-warcraft)
- **Base URL:** `https://us.api.blizzard.com`

#### Tags

- World of Warcraft
- Game Data
- Profile
- Auctions
- Characters

#### Properties

- [Documentation](https://develop.battle.net/documentation/world-of-warcraft/game-data-apis)
- [Authentication](https://develop.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/blizzard-world-of-warcraft-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blizzard-world-of-warcraft.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blizzard-world-of-warcraft.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Diablo III Community API

Battle.net Community and Game Data API for Diablo III providing access to acts, artisans, recipes, followers, character classes, items, item types, and player career/hero profile data. Like other Battle.net APIs, endpoints use regional hosts and require an OAuth 2.0 client credentials access token.

- **Human URL:** [https://develop.battle.net/documentation/diablo-3](https://develop.battle.net/documentation/diablo-3)
- **Base URL:** `https://us.api.blizzard.com`

#### Tags

- Diablo III
- Game Data
- Profile
- Items

#### Properties

- [Documentation](https://develop.battle.net/documentation/diablo-3/community-apis)
- [Authentication](https://develop.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/blizzard-diablo-iii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blizzard-diablo-iii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blizzard-diablo-iii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### StarCraft II Community API

Battle.net Community API for StarCraft II providing access to ladder data, player profiles, legacy profiles, and grandmaster leaderboards. Requires an OAuth 2.0 client credentials access token issued by https://oauth.battle.net.

- **Human URL:** [https://develop.battle.net/documentation/starcraft-2](https://develop.battle.net/documentation/starcraft-2)
- **Base URL:** `https://us.api.blizzard.com`

#### Tags

- StarCraft II
- Game Data
- Profile
- Ladder

#### Properties

- [Documentation](https://develop.battle.net/documentation/starcraft-2/community-apis)
- [Authentication](https://develop.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/blizzard-starcraft-ii-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blizzard-starcraft-ii.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blizzard-starcraft-ii.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Hearthstone Game Data API

Battle.net Game Data API for Hearthstone providing access to card sets, individual cards, card backs, card decks (deck codes), and metadata such as classes, sets, rarities, types, and game modes. Card and metadata lookups support locale-aware responses. Requires an OAuth 2.0 client credentials access token.

- **Human URL:** [https://develop.battle.net/documentation/hearthstone](https://develop.battle.net/documentation/hearthstone)
- **Base URL:** `https://us.api.blizzard.com`

#### Tags

- Hearthstone
- Game Data
- Cards
- Decks

#### Properties

- [Documentation](https://develop.battle.net/documentation/hearthstone/game-data-apis)
- [Authentication](https://develop.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/blizzard-hearthstone-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blizzard-hearthstone.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blizzard-hearthstone.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Battle.net OAuth API

OAuth 2.0 authorization server for the Battle.net developer platform. Supports the authorization code flow for user-context access (Battle.net account login and profile scopes such as wow.profile, sc2.profile, d3.profile, openid) and the client credentials flow for accessing the public Game Data APIs. Hosted at https://oauth.battle.net.

- **Human URL:** [https://develop.battle.net/documentation/guides/using-oauth](https://develop.battle.net/documentation/guides/using-oauth)
- **Base URL:** `https://oauth.battle.net`

#### Tags

- OAuth
- Authentication
- Authorization
- OpenID Connect

#### Properties

- [Documentation](https://develop.battle.net/documentation/guides/using-oauth)
- [OpenAPI](openapi/blizzard-oauth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/blizzard-oauth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/blizzard-oauth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Blizzard)
- [LinkedIn](https://www.linkedin.com/company/blizzard-entertainment)
- [Website](https://www.blizzard.com/)
- [Portal](https://develop.battle.net/)
- [Documentation](https://develop.battle.net/documentation)
- [Getting Started](https://develop.battle.net/documentation/guides/getting-started)
- [Authentication](https://develop.battle.net/documentation/guides/using-oauth)
- [Terms of Service](https://www.blizzard.com/legal/8b946525-de01-481a-9f4f-89af2c4f5d29/blizzard-end-user-license-agreement)
- [Privacy Policy](https://www.blizzard.com/legal/fba4d00f-c7e4-4883-b8b9-1b4500a402ea/blizzard-entertainment-privacy-notice)
- [Forum](https://us.forums.blizzard.com/en/blizzard/c/api-discussion/18)
- [Spectral Rules](rules/blizzard-entertainment-rules.yml)
- [Vocabulary](vocabulary/blizzard-entertainment-vocabulary.yaml)
- [JSON-LD](json-ld/blizzard-entertainment-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Plans](plans/blizzard-entertainment-plans-pricing.yml)
- [Rate Limits](rate-limits/blizzard-entertainment-rate-limits.yml)
- [Fin Ops](finops/blizzard-entertainment-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Compliance](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
