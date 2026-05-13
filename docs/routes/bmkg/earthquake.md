# BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian) - Recent Earthquakes

## Coverage
`index-only`

## Route
- Namespace: `bmkg`
- Namespace Name: `BADAN METEOROLOGI, KLIMATOLOGI, DAN GEOFISIKA(Indonesian)`
- Route Path: `/earthquake`
- Route Name: `Recent Earthquakes`
- Example: `/bmkg/earthquake`
- URL: `bmkg.go.id/`
- Language: `en`
- Categories: `forecast`
- Maintainers: `Shinanory`
- Source Location: `earthquake.ts`
- Source Module: `() => import('@/routes/bmkg/earthquake.ts')`

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
  - `bmkg.go.id/gempabumi-terkini.html`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/bmkg/earthquake",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "earthquake.ts",
  "maintainers": [
    "Shinanory"
  ],
  "module": "() => import('@/routes/bmkg/earthquake.ts')",
  "name": "Recent Earthquakes",
  "parameters": {},
  "path": "/earthquake",
  "radar": [
    {
      "source": [
        "bmkg.go.id/",
        "bmkg.go.id/gempabumi-terkini.html"
      ]
    }
  ],
  "url": "bmkg.go.id/"
}
```
