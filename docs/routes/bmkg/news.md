# BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian) - News

## Coverage
`index-only`

## Route
- Namespace: `bmkg`
- Namespace Name: `BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian)`
- Route Path: `/news`
- Route Name: `News`
- Example: `/bmkg/news`
- URL: `bmkg.go.id/`
- Language: `en`
- Categories: `forecast`
- Maintainers: `Shinanory`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/bmkg/news.ts')`

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
  - `bmkg.go.id/`
  - `bmkg.go.id/berita`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/bmkg/news",
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
    "Shinanory"
  ],
  "module": "() => import('@/routes/bmkg/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "bmkg.go.id/",
        "bmkg.go.id/berita"
      ]
    }
  ],
  "url": "bmkg.go.id/"
}
```
