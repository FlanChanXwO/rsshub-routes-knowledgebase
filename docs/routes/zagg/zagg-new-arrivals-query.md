# Zagg - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `zagg`
- Namespace Name: `Zagg`
- Route Path: `/zagg/new-arrivals/:query?`
- Route Name: `New Arrivals`
- Example: `/zagg/new-arrivals/brand=164&cat=3038,3041`
- URL: `zagg.com`
- Language: `_None_`
- Categories: `shopping`
- Maintainers: `EthanWng97`
- Source Location: `new-arrivals.tsx`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "new-arrivals.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "New Arrivals",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/new-arrivals/:query?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
