# Komiic - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `komiic`
- Namespace Name: `Komiic`
- Route Path: `/comic/:id`
- Route Name: `漫画更新`
- Example: `/komiic/comic/533`
- URL: `komiic.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `NekoAria`
- Source Location: `comic.ts`
- Source Module: `() => import('@/routes/komiic/comic.ts')`

## Description
_None_

## Parameters
- `id`: 漫画 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `komiic.com/comic/:id`
- `target`: `/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/komiic/comic/533",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "comic.ts",
  "maintainers": [
    "NekoAria"
  ],
  "module": "() => import('@/routes/komiic/comic.ts')",
  "name": "漫画更新",
  "parameters": {
    "id": "漫画 ID"
  },
  "path": "/comic/:id",
  "radar": [
    {
      "source": [
        "komiic.com/comic/:id"
      ],
      "target": "/comic/:id"
    }
  ]
}
```
