# 歪脑 - 歪脑读

## Coverage
`index-only`

## Route
- Namespace: `wainao`
- Namespace Name: `歪脑`
- Route Path: `/wainao/wainao-reads`
- Route Name: `歪脑读`
- Example: `/wainao/wainao-reads`
- URL: `www.wainao.me`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `lucky13820`
- Source Location: `wainao-reads.ts`
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

## Radar
### Rule 1
- `source`:
  - `www.wainao.me`
  - `www.wainao.me/wainao-reads`
- `target`: `/wainao-reads`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/wainao/wainao-reads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 54,
  "location": "wainao-reads.ts",
  "maintainers": [
    "lucky13820"
  ],
  "name": "歪脑读",
  "path": "/wainao-reads",
  "radar": [
    {
      "source": [
        "www.wainao.me",
        "www.wainao.me/wainao-reads"
      ],
      "target": "/wainao-reads"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "歪脑读 - 歪脑 - Powered by RSSHub",
      "errorAt": "2025-03-06T03:05:51.618Z",
      "errorMessage": "404 Not Found\nterminated\nterminated\nterminated\nterminated\n",
      "id": "109801824683778048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wainao.me/",
      "title": "歪脑读 - 歪脑",
      "type": "feed",
      "url": "rsshub://wainao/wainao-reads"
    }
  ],
  "url": "www.wainao.me"
}
```
