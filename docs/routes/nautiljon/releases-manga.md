# Nautiljon - France manga releases

## Coverage
`index-only`

## Route
- Namespace: `nautiljon`
- Namespace Name: `Nautiljon`
- Route Path: `/releases/manga`
- Route Name: `France manga releases`
- Example: `/nautiljon/releases/manga`
- URL: `nautiljon.com`
- Language: `fr`
- Categories: `reading`
- Maintainers: `Fafnor`
- Source Location: `manga-releases.ts`
- Source Module: `() => import('@/routes/nautiljon/manga-releases.ts')`

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
  - `nautiljon.com/`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/nautiljon/releases/manga",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga-releases.ts",
  "maintainers": [
    "Fafnor"
  ],
  "module": "() => import('@/routes/nautiljon/manga-releases.ts')",
  "name": "France manga releases",
  "parameters": {},
  "path": "/releases/manga",
  "radar": [
    {
      "source": [
        "nautiljon.com/"
      ]
    }
  ],
  "url": "nautiljon.com"
}
```
