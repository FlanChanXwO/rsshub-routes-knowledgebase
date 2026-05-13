# 数字尾巴 - 兴趣

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/feed`
- Route Name: `兴趣`
- Example: `/dgtle/feed`
- URL: `www.dgtle.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `feed.ts`
- Source Module: `() => import('@/routes/dgtle/feed.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.dgtle.com/feed`
- `target`: `/feed`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dgtle/feed",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "feed.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dgtle/feed.ts')",
  "name": "兴趣",
  "path": "/feed",
  "radar": [
    {
      "source": [
        "www.dgtle.com/feed"
      ],
      "target": "/feed"
    }
  ],
  "url": "www.dgtle.com",
  "view": 0
}
```
