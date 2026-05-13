# Discord - Quests

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/quests`
- Route Name: `Quests`
- Example: `/discord/quests`
- URL: `discord.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `quest.ts`
- Source Module: `() => import('@/routes/discord/quest.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "Discord authorization header", "name": "DISCORD_AUTHORIZATION"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `discord.com/quest-home`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/discord/quests",
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
  "location": "quest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/discord/quest.ts')",
  "name": "Quests",
  "path": "/quests",
  "radar": [
    {
      "source": [
        "discord.com/quest-home"
      ]
    }
  ]
}
```
