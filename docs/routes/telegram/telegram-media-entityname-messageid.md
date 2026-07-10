# Telegram - Channel Media

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/telegram/media/:entityName/:messageId`
- Route Name: `Channel Media`
- Example: `/telegram/media/telegram/1233`
- URL: `t.me`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `synchrone`
- Source Location: `channel-media.ts`
- Source Module: `_None_`

## Description
::: tip
Serves telegram media like pictures, video or files.
:::

## Parameters
- `entityName`: entity name
- `messageId`: message id


## Features
- `requireConfig`: [{"description": "Telegram API Authentication", "name": "TELEGRAM_SESSION", "optional": false}]
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
  "description": "::: tip\nServes telegram media like pictures, video or files.\n:::",
  "example": "/telegram/media/telegram/1233",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "Telegram API Authentication",
        "name": "TELEGRAM_SESSION",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel-media.ts",
  "maintainers": [
    "synchrone"
  ],
  "name": "Channel Media",
  "parameters": {
    "entityName": "entity name",
    "messageId": "message id"
  },
  "path": "/media/:entityName/:messageId",
  "radar": [],
  "topFeeds": []
}
```
