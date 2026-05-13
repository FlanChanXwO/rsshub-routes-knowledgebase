# Telegram - Channel Media

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/media/:entityName/:messageId`
- Route Name: `Channel Media`
- Example: `/telegram/media/telegram/1233`
- URL: `t.me`
- Language: `en`
- Categories: `social-media`
- Maintainers: `synchrone`
- Source Location: `channel-media.ts`
- Source Module: `() => import('@/routes/telegram/channel-media.ts')`

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
  "description": "\n::: tip\n  Serves telegram media like pictures, video or files.\n:::\n",
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
  "location": "channel-media.ts",
  "maintainers": [
    "synchrone"
  ],
  "module": "() => import('@/routes/telegram/channel-media.ts')",
  "name": "Channel Media",
  "parameters": {
    "entityName": "entity name",
    "messageId": "message id"
  },
  "path": "/media/:entityName/:messageId",
  "radar": []
}
```
