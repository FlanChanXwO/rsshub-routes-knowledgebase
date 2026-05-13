# Polymarket - Series

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/series/:slug?`
- Route Name: `Series`
- Example: `/polymarket/series`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `series.ts`
- Source Module: `() => import('@/routes/polymarket/series.ts')`

## Description
_None_

## Parameters
- `slug`: {"default": "all", "description": "Series slug, e.g. nfl, nba, mlb. If omitted, lists all series."}


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
  - `polymarket.com/series/:slug`
- `target`: `/series/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/series",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "series.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/series.ts')",
  "name": "Series",
  "parameters": {
    "slug": {
      "default": "all",
      "description": "Series slug, e.g. nfl, nba, mlb. If omitted, lists all series."
    }
  },
  "path": "/series/:slug?",
  "radar": [
    {
      "source": [
        "polymarket.com/series/:slug"
      ],
      "target": "/series/:slug"
    }
  ],
  "url": "polymarket.com"
}
```
