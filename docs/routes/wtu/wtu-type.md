# 武汉纺织大学 - 信息门户公告

## Coverage
`index-only`

## Route
- Namespace: `wtu`
- Namespace Name: `武汉纺织大学`
- Route Path: `/wtu/:type`
- Route Name: `信息门户公告`
- Example: `/wtu/2`
- URL: `wtu.91wllm.com`
- Language: `_None_`
- Categories: `university`
- Maintainers: `loyio`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 公告类型 | 通知公告 | 教务信息 | 科研动态 |
| -------- | -------- | -------- | -------- |
| 参数     | 1        | 2        | 3        |

## Parameters
- `type`: 公告类型，详见表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 公告类型 | 通知公告 | 教务信息 | 科研动态 |\n| -------- | -------- | -------- | -------- |\n| 参数     | 1        | 2        | 3        |",
  "example": "/wtu/2",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "loyio"
  ],
  "name": "信息门户公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
