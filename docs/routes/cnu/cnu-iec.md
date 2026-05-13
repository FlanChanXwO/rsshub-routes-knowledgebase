# 首都师范大学 - 信息工程学院通知公告

## Coverage
`index-only`

## Route
- Namespace: `cnu`
- Namespace Name: `首都师范大学`
- Route Path: `/cnu/iec`
- Route Name: `信息工程学院通知公告`
- Example: `/cnu/iec`
- URL: `iec.cnu.edu.cn/ggml/tzgg1/index.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `liueic`
- Source Location: `iec.ts`
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
  - `iec.cnu.edu.cn/ggml/tzgg1/index.htm`
- `target`: `/cnu/iec`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/cnu/iec",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "iec.ts",
  "maintainers": [
    "liueic"
  ],
  "name": "信息工程学院通知公告",
  "parameters": {},
  "path": "/iec",
  "radar": [
    {
      "source": [
        "iec.cnu.edu.cn/ggml/tzgg1/index.htm"
      ],
      "target": "/cnu/iec"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processTimers (node:internal/timers:538:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "iec.cnu.edu.cn/ggml/tzgg1/index.htm"
}
```
