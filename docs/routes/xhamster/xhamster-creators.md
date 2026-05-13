# xHamster - Newest Videos by Creator

## Coverage
`index-only`

## Route
- Namespace: `xhamster`
- Namespace Name: `xHamster`
- Route Path: `/xhamster/:creators`
- Route Name: `Newest Videos by Creator`
- Example: `/xhamster/faustina-pierre`
- URL: `xhamster.com/faustina-pierre/newest`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `eve2ptp`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `creators`: Creator slug from the URL (e.g. `faustina-pierre`)


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
  - `xhamster.com/creators/:creators`
  - `xhamster.com/creators/:creators/newest`
- `target`: `/:creators`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/xhamster/faustina-pierre",
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
  "location": "index.ts",
  "maintainers": [
    "eve2ptp"
  ],
  "name": "Newest Videos by Creator",
  "parameters": {
    "creators": "Creator slug from the URL (e.g. `faustina-pierre`)"
  },
  "path": "/:creators",
  "radar": [
    {
      "source": [
        "xhamster.com/creators/:creators",
        "xhamster.com/creators/:creators/newest"
      ],
      "target": "/:creators"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "xhamster.com/faustina-pierre/newest"
}
```
