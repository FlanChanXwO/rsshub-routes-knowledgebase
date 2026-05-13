# Polymarket - Search

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/search/:query`
- Route Name: `Search`
- Example: `/polymarket/search/trump`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/polymarket/search.ts')`

## Description
_None_

## Parameters
- `query`: Search query


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
    "finance"
  ],
  "example": "/polymarket/search/trump",
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
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/search.ts')",
  "name": "Search",
  "parameters": {
    "query": "Search query"
  },
  "path": "/search/:query",
  "url": "polymarket.com"
}
```
