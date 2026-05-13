# Grist - Series

## Coverage
`index-only`

## Route
- Namespace: `grist`
- Namespace Name: `Grist`
- Route Path: `/series/:series`
- Route Name: `Series`
- Example: `/grist/series/best-of-grist`
- URL: `grist.org/articles/`
- Language: `en`
- Categories: `new-media`
- Maintainers: `Rjnishant530`
- Source Location: `series.ts`
- Source Module: `() => import('@/routes/grist/series.ts')`

## Description
_None_

## Parameters
- `series`: Find in the URL which has /series/


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
  - `grist.org/series/:series`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/grist/series/best-of-grist",
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
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/grist/series.ts')",
  "name": "Series",
  "parameters": {
    "series": "Find in the URL which has /series/"
  },
  "path": "/series/:series",
  "radar": [
    {
      "source": [
        "grist.org/series/:series"
      ]
    }
  ],
  "url": "grist.org/articles/"
}
```
