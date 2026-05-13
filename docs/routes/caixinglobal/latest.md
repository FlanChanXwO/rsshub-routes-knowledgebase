# Caixin Global - Latest News

## Coverage
`index-only`

## Route
- Namespace: `caixinglobal`
- Namespace Name: `Caixin Global`
- Route Path: `/latest`
- Route Name: `Latest News`
- Example: `/caixinglobal/latest`
- URL: `caixinglobal.com/news`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/caixinglobal/latest.ts')`

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
  - `caixinglobal.com/news`
  - `caixinglobal.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/caixinglobal/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/caixinglobal/latest.ts')",
  "name": "Latest News",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "caixinglobal.com/news",
        "caixinglobal.com/"
      ]
    }
  ],
  "url": "caixinglobal.com/news"
}
```
