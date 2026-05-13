# 山东大学 - 研工部

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/ygb/:type?`
- Route Name: `研工部`
- Example: `/sdu/ygb/zytz`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `kukeya`
- Source Location: `ygb.ts`
- Source Module: `_None_`

## Description
| 重要通知 | 管理服务 | 创新实践 |
| -------- | -------- | -------- |
| zytz     | glfw     | cxsj     |

## Parameters
- `type`: 默认为`zytz`


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
  "description": "| 重要通知 | 管理服务 | 创新实践 |\n| -------- | -------- | -------- |\n| zytz     | glfw     | cxsj     |",
  "example": "/sdu/ygb/zytz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ygb.ts",
  "maintainers": [
    "kukeya"
  ],
  "name": "研工部",
  "parameters": {
    "type": "默认为`zytz`"
  },
  "path": "/ygb/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
