# 蜻蜓 FM - 专辑

## Coverage
`index-only`

## Route
- Namespace: `qingting`
- Namespace Name: `蜻蜓 FM`
- Route Path: `/channel/:id`
- Route Name: `专辑`
- Example: `/qingting/channel/293411`
- URL: `qingting.fm`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `channel.ts`
- Source Module: `() => import('@/routes/qingting/channel.ts')`

## Description
_None_

## Parameters
- `id`: 专辑id, 可在专辑页 URL 中找到


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
    "multimedia"
  ],
  "example": "/qingting/channel/293411",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "channel.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qingting/channel.ts')",
  "name": "专辑",
  "parameters": {
    "id": "专辑id, 可在专辑页 URL 中找到"
  },
  "path": "/channel/:id"
}
```
