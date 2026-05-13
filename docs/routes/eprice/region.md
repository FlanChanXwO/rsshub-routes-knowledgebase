# ePrice - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `eprice`
- Namespace Name: `ePrice`
- Route Path: `/:region?`
- Route Name: `最新消息`
- Example: `/eprice/tw`
- URL: `eprice.com.tw`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `rss.tsx`
- Source Module: `() => import('@/routes/eprice/rss.tsx')`

## Description
地区：

| hk   | tw   |
| ---- | ---- |
| 香港 | 台湾 |

## Parameters
- `region`: 地区，预设为 tw


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
    "new-media"
  ],
  "description": "地区：\n\n| hk   | tw   |\n| ---- | ---- |\n| 香港 | 台湾 |",
  "example": "/eprice/tw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rss.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/eprice/rss.tsx')",
  "name": "最新消息",
  "parameters": {
    "region": "地区，预设为 tw"
  },
  "path": "/:region?"
}
```
