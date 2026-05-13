# 浙江工业大学 - 设计与建筑学院

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/zjut/da/:type`
- Route Name: `设计与建筑学院`
- Example: `/zjut/da/1`
- URL: `www.design.zjut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `yikZero`
- Source Location: `da/index.ts`
- Source Module: `_None_`

## Description
| 学院新闻 | 公告通知 | 科研申报 | 科研成果 | 文件与资源 | 学术交流 |
| -------- | -------- | -------- | -------- | ---------- | -------- |
| 1        | 2        | 3        | 4        | 5          | 6        |

## Parameters
- `type`: 分类，见下表


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
  "description": "| 学院新闻 | 公告通知 | 科研申报 | 科研成果 | 文件与资源 | 学术交流 |\n| -------- | -------- | -------- | -------- | ---------- | -------- |\n| 1        | 2        | 3        | 4        | 5          | 6        |",
  "example": "/zjut/da/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "da/index.ts",
  "maintainers": [
    "yikZero"
  ],
  "name": "设计与建筑学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/da/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.design.zjut.edu.cn"
}
```
