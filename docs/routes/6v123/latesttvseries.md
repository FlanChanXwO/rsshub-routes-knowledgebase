# 6v 电影 - 最新电视剧

## Coverage
`index-only`

## Route
- Namespace: `6v123`
- Namespace Name: `6v 电影`
- Route Path: `/latestTVSeries`
- Route Name: `最新电视剧`
- Example: `/6v123/latestTVSeries`
- URL: `hao6v.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `tc9011`
- Source Location: `latest-tvseries.ts`
- Source Module: `() => import('@/routes/6v123/latest-tvseries.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hao6v.com/`
  - `hao6v.com/gvod/dsj.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/6v123/latestTVSeries",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest-tvseries.ts",
  "maintainers": [
    "tc9011"
  ],
  "module": "() => import('@/routes/6v123/latest-tvseries.ts')",
  "name": "最新电视剧",
  "parameters": {},
  "path": "/latestTVSeries",
  "radar": [
    {
      "source": [
        "hao6v.com/",
        "hao6v.com/gvod/dsj.html"
      ]
    }
  ],
  "url": "hao6v.com/"
}
```
