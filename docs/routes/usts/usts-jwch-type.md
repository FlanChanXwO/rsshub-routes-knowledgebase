# 苏州科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `usts`
- Namespace Name: `苏州科技大学`
- Route Path: `/usts/jwch/:type?`
- Route Name: `教务处`
- Example: `/usts/jwch`
- URL: `jwch.usts.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `None`
- Source Location: `jwch.ts`
- Source Module: `_None_`

## Description
| 类型 | 教务动态 | 公告在线 | 选课通知 |
| ---- | -------- | -------- | -------- |
|      | jwdt     | ggzx     | xktz     |

## Parameters
- `type`: 类型，默认为教务动态


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
  "description": "| 类型 | 教务动态 | 公告在线 | 选课通知 |\n| ---- | -------- | -------- | -------- |\n|      | jwdt     | ggzx     | xktz     |",
  "example": "/usts/jwch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jwch.ts",
  "maintainers": [],
  "name": "教务处",
  "parameters": {
    "type": "类型，默认为教务动态"
  },
  "path": "/jwch/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
