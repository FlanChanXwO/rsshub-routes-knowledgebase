# GQ - News

## Coverage
`index-only`

## Route
- Namespace: `gq`
- Namespace Name: `GQ`
- Route Path: `/news`
- Route Name: `News`
- Example: `/gq/news`
- URL: `gq.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `EthanWng97`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/gq/news.ts')`

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
  - `gq.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/gq/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/gq/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "gq.com/"
      ]
    }
  ],
  "view": 0
}
```
