# Zagg - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `zagg`
- Namespace Name: `Zagg`
- Route Path: `/new-arrivals/:query?`
- Route Name: `New Arrivals`
- Example: `/zagg/new-arrivals/brand=164&cat=3038,3041`
- URL: `zagg.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `new-arrivals.tsx`
- Source Module: `() => import('@/routes/zagg/new-arrivals.tsx')`

## Description
For instance, in `https://www.zagg.com/en_us/new-arrivals?brand=164&cat=3038%2C3041`, the query is `brand=164&cat=3038%2C3041`

## Parameters
- `query`: query, search page querystring


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
    "shopping"
  ],
  "description": "For instance, in `https://www.zagg.com/en_us/new-arrivals?brand=164&cat=3038%2C3041`, the query is `brand=164&cat=3038%2C3041`",
  "example": "/zagg/new-arrivals/brand=164&cat=3038,3041",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "new-arrivals.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/zagg/new-arrivals.tsx')",
  "name": "New Arrivals",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/new-arrivals/:query?"
}
```
