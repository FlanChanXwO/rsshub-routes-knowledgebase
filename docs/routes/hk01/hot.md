# 香港 01 - 热门

## Coverage
`index-only`

## Route
- Namespace: `hk01`
- Namespace Name: `香港 01`
- Route Path: `/hot`
- Route Name: `热门`
- Example: `/hk01/hot`
- URL: `hk01.com/hot`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `hoilc, Fatpandac, nczitzk`
- Source Location: `hot.ts`
- Source Module: `() => import('@/routes/hk01/hot.ts')`

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
  - `hk01.com/hot`
  - `hk01.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hk01/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot.ts",
  "maintainers": [
    "hoilc",
    "Fatpandac",
    "nczitzk"
  ],
  "module": "() => import('@/routes/hk01/hot.ts')",
  "name": "热门",
  "parameters": {},
  "path": "/hot",
  "radar": [
    {
      "source": [
        "hk01.com/hot",
        "hk01.com/"
      ]
    }
  ],
  "url": "hk01.com/hot"
}
```
