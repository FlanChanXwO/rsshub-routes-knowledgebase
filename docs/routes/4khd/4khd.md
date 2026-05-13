# 4KHD - Latest

## Coverage
`index-only`

## Route
- Namespace: `4khd`
- Namespace Name: `4KHD`
- Route Path: `/4khd/`
- Route Name: `Latest`
- Example: `/4khd`
- URL: `www.4khd.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `latest.ts`
- Source Module: `_None_`

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
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.4khd.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4khd",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "latest.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Latest",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "www.4khd.com/"
      ],
      "target": ""
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.4khd.com/"
}
```
