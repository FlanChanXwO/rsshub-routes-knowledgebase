# Discord - Guild Search

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/search/:guildId/:routeParams`
- Route Name: `Guild Search`
- Example: `/discord/search/302094807046684672/content=friendly&has=image,video`
- URL: `discord.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `NekoAria`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/discord/search.ts')`

## Description
_None_

## Parameters
- `guildId`: Guild ID
- `routeParams`: Search parameters, support content, author_id, mentions, has, min_id, max_id, channel_id, pinned


## Features
- `requireConfig`: [{"description": "Discord authorization header", "name": "DISCORD_AUTHORIZATION"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/discord/search/302094807046684672/content=friendly&has=image,video",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Discord authorization header",
        "name": "DISCORD_AUTHORIZATION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "NekoAria"
  ],
  "module": "() => import('@/routes/discord/search.ts')",
  "name": "Guild Search",
  "parameters": {
    "guildId": "Guild ID",
    "routeParams": "Search parameters, support content, author_id, mentions, has, min_id, max_id, channel_id, pinned"
  },
  "path": "/search/:guildId/:routeParams"
}
```
