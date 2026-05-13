# TrendForce - News

## Coverage
`index-only`

## Route
- Namespace: `trendforce`
- Namespace Name: `TrendForce`
- Route Path: `/news`
- Route Name: `News`
- Example: `/trendforce/news`
- URL: `www.trendforce.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `new.ts`
- Source Module: `() => import('@/routes/trendforce/new.ts')`

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
  - `www.trendforce.com/news/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/trendforce/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "new.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/trendforce/new.ts')",
  "name": "News",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.trendforce.com/news/"
      ],
      "target": "/news"
    }
  ],
  "url": "www.trendforce.com",
  "view": 0
}
```
