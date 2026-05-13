# 潍坊学院 - 教务处通知

## Coverage
`index-only`

## Route
- Namespace: `wfu`
- Namespace Name: `潍坊学院`
- Route Path: `/wfu/jwc`
- Route Name: `教务处通知`
- Example: `/wfu/jwc`
- URL: `jwc.wfu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cccht`
- Source Location: `jwc.ts`
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
  - `jwc.wfu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/wfu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwc.ts",
  "maintainers": [
    "cccht"
  ],
  "name": "教务处通知",
  "parameters": {},
  "path": "/jwc",
  "radar": [
    {
      "source": [
        "jwc.wfu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jwc.wfu.edu.cn/"
}
```
