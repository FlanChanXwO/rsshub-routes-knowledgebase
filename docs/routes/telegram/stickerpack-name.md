# Telegram - Sticker Pack

## Coverage
`index-only`

## Route
- Namespace: `telegram`
- Namespace Name: `Telegram`
- Route Path: `/stickerpack/:name`
- Route Name: `Sticker Pack`
- Example: `/telegram/stickerpack/DIYgod`
- URL: `t.me`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `stickerpack.ts`
- Source Module: `() => import('@/routes/telegram/stickerpack.ts')`

## Description
_None_

## Parameters
- `name`: Sticker Pack name, available in the sharing URL


## Features
- `requireConfig`: false
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
  "example": "/telegram/stickerpack/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "stickerpack.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/telegram/stickerpack.ts')",
  "name": "Sticker Pack",
  "parameters": {
    "name": "Sticker Pack name, available in the sharing URL"
  },
  "path": "/stickerpack/:name",
  "view": 2
}
```
