# BaoBua - Search

## Coverage
`index-only`

## Route
- Namespace: `baobua`
- Namespace Name: `BaoBua`
- Route Path: `/search/:keyword`
- Route Name: `Search`
- Example: `/baobua/search/cos`
- URL: `baobua.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/baobua/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
  - `baobua.com/search`
- `target`: `/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/baobua/search/cos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "module": "() => import('@/routes/baobua/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "baobua.com/search"
      ],
      "target": "/search/:keyword"
    }
  ],
  "url": "baobua.com/"
}
```
