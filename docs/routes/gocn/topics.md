# GoCN - 每日新闻

## Coverage
`index-only`

## Route
- Namespace: `gocn`
- Namespace Name: `GoCN`
- Route Path: `/topics`
- Route Name: `每日新闻`
- Example: `/gocn/topics`
- URL: `gocn.vip/`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `AtlanCI, CcccFz`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/gocn/topics.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gocn.vip/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gocn/topics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "topics.ts",
  "maintainers": [
    "AtlanCI",
    "CcccFz"
  ],
  "module": "() => import('@/routes/gocn/topics.ts')",
  "name": "每日新闻",
  "parameters": {},
  "path": "/topics",
  "radar": [
    {
      "source": [
        "gocn.vip/"
      ]
    }
  ],
  "url": "gocn.vip/"
}
```
