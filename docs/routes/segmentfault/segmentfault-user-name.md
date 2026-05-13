# SegmentFault - 用户

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/segmentfault/user/:name`
- Route Name: `用户`
- Example: `/segmentfault/user/minnanitkong`
- URL: `segmentfault.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `leyuuu, Fatpandac`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `name`: 用户 Id，用户详情页 URL 可以找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `segmentfault.com/u/:name`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/user/minnanitkong",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "leyuuu",
    "Fatpandac"
  ],
  "name": "用户",
  "parameters": {
    "name": "用户 Id，用户详情页 URL 可以找到"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "segmentfault.com/u/:name"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
