# Grist - Series

## Coverage
`index-only`

## Route
- Namespace: `grist`
- Namespace Name: `Grist`
- Route Path: `/grist/series/:series`
- Route Name: `Series`
- Example: `/grist/series/best-of-grist`
- URL: `grist.org/articles/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `Rjnishant530`
- Source Location: `series.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "series.ts",
  "maintainers": [
    "Rjnishant530"
  ],
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
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "grist.org/articles/"
}
```
