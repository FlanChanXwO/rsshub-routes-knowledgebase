# 山东大学 - 青岛校区学科建设与研究生教育办公室

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/qd/xyb/:type?`
- Route Name: `青岛校区学科建设与研究生教育办公室`
- Example: `/sdu/qd/xyb/gztz`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `kukeya`
- Source Location: `qd/xyb.ts`
- Source Module: `_None_`

## Description
| 工作通知 |
| -------- |
| gztz     |

## Parameters
- `type`: 默认为`gztz`


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
    "university"
  ],
  "description": "| 工作通知 |\n| -------- |\n| gztz     |",
  "example": "/sdu/qd/xyb/gztz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "qd/xyb.ts",
  "maintainers": [
    "kukeya"
  ],
  "name": "青岛校区学科建设与研究生教育办公室",
  "parameters": {
    "type": "默认为`gztz`"
  },
  "path": "/qd/xyb/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
