# Plurk - Search

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/search/:keyword`
- Route Name: `Search`
- Example: `/plurk/search/FGO`
- URL: `plurk.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/plurk/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/plurk/search/FGO",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/plurk/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword"
  },
  "path": "/search/:keyword"
}
```
