# Discord - Quests

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/discord/quests`
- Route Name: `Quests`
- Example: `/discord/quests`
- URL: `discord.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `quest.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "quest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Quests",
  "path": "/quests",
  "radar": [
    {
      "source": [
        "discord.com/quest-home"
      ]
    }
  ],
  "topFeeds": []
}
```
