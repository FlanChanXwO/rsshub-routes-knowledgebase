# Western Digital - Download

## Coverage
`index-only`

## Route
- Namespace: `wdc`
- Namespace Name: `Western Digital`
- Route Path: `/wdc/download/:id?`
- Route Name: `Download`
- Example: `/wdc/download/279`
- URL: `support.wdc.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `None`
- Source Location: `download.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Software id, can be found in URL, 279 as Western Digital Dashboard by default


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
    "program-update"
  ],
  "example": "/wdc/download/279",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "download.ts",
  "maintainers": [],
  "name": "Download",
  "parameters": {
    "id": "Software id, can be found in URL, 279 as Western Digital Dashboard by default"
  },
  "path": "/download/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
