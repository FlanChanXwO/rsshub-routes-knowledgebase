# 山东大学 - 研究生招生信息网

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/yz/:type?`
- Route Name: `研究生招生信息网`
- Example: `/sdu/yz/tzgg`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `niuyi1017`
- Source Location: `yz.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 招生拓展 | 政策文件 |
| -------- | -------- | -------- |
| tzgg     | zstz     | zcwj     |

## Parameters
- `type`: 默认为`tzgg`


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
  "description": "| 通知公告 | 招生拓展 | 政策文件 |\n| -------- | -------- | -------- |\n| tzgg     | zstz     | zcwj     |",
  "example": "/sdu/yz/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "yz.ts",
  "maintainers": [
    "niuyi1017"
  ],
  "name": "研究生招生信息网",
  "parameters": {
    "type": "默认为`tzgg`"
  },
  "path": "/yz/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
