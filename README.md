# Blizzard Entertainment (blizzard-entertainment)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
