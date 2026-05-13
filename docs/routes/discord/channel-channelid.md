# Discord - Channel Messages

## Coverage
`index-only`

## Route
- Namespace: `discord`
- Namespace Name: `Discord`
- Route Path: `/channel/:channelId`
- Route Name: `Channel Messages`
- Example: `/discord/channel/950465850056536084`
- URL: `discord.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/discord/channel.ts')`

## Description
_None_

## Parameters
- `channelId`: Channel ID


## Features
- `requireConfig`: [{"description": "Discord authorization header from the browser", "name": "DISCORD_AUTHORIZATION"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `discord.com/channels/:guildId/:channelId/:messageID`
  - `discord.com/channels/:guildId/:channelId`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/discord/channel/950465850056536084",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Discord authorization header from the browser",
        "name": "DISCORD_AUTHORIZATION"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/discord/channel.ts')",
  "name": "Channel Messages",
  "parameters": {
    "channelId": "Channel ID"
  },
  "path": "/channel/:channelId",
  "radar": [
    {
      "source": [
        "discord.com/channels/:guildId/:channelId/:messageID",
        "discord.com/channels/:guildId/:channelId"
      ]
    }
  ]
}
```
